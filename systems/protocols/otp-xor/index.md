# OTP-XOR Encryption System

*One-time pad XOR encryption — the cryptographic backbone of OTP22.*

---

## Overview

OTP22 takes its name from the **One-Time Pad (OTP)** cryptographic system. XOR-based one-time pads are used throughout the game for encrypting narrative messages, agent communications, and data files.

The OTP is theoretically unbreakable when:
1. The key material is truly random
2. Each key portion is used only once
3. The key is at least as long as the plaintext
4. The key is kept secret

OTP22 satisfies all these conditions. The key material comes from physical dead drops, making it inaccessible to anyone who doesn't retrieve the physical item.

---

## Key Files

### otp-blue-1.bin
**Size:** ~1 GB
**Source:** El Paso, TX dead drop (December 2012, original run)
**Used for:** XORFS messages (AS32 codes 18000–19999, 22000–22999)

This is the master key file for the revival-era messaging system. Each XORFS message specifies a byte offset into this file; the decryption extracts the appropriate number of bytes and XORs them against the ciphertext.

The 1 GB size allows for enormous amounts of message material before key reuse — at typical message lengths of a few hundred bytes, this key could support hundreds of thousands of messages.

### Slate Deposits in the Intermountain West (Book)
**Format:** Physical book, 365 rows × 32 numbers × 3 sections
**Used for:** Slate messages (AS32 codes 301, 302, 303)

The book itself is the key. Each row corresponds to a sequence number. Players must own a physical copy to decrypt Slate messages.

### Original Run CDs
The original run used key material distributed on physical CDs in dead drops:
- **OTP7, OTP8, OTP9** — Kauai, HI drops (March 2013)
- **North Dakota CD** — North Dakota drop (February 2013)
- **El Paso CD** — El Paso, TX drop (December 2012)
- Various other drop CDs

Each CD was labeled with its OTP number. Messages in the 18xxx range specified which OTP file to use.

---

## XOR Decryption

The XOR operation is simple:

```
plaintext_byte = ciphertext_byte XOR key_byte
```

Applied byte-by-byte across the entire message. Because XOR is its own inverse, the same operation both encrypts and decrypts:

```
ciphertext_byte = plaintext_byte XOR key_byte
```

**Example:**
```
ciphertext: 0x4A 0x1F 0x33 ...
key:        0x26 0x7C 0x58 ...
plaintext:  0x6C 0x63 0x6B ...  → "lck..."
```

---

## XORFS Message Format

Messages delivered via NATO phonetic alphabet over the phone:

```
Blue OTP 1 file start
[hex bytes spoken as NATO phonetic: Alpha=A, Bravo=B, etc.]
[decimal offset]
End of message. Cheers.
```

**Decryption steps:**
1. Transcribe NATO phonetic to hex string
2. Convert hex to byte array (ciphertext)
3. Open `otp-blue-1.bin` at specified offset
4. XOR ciphertext against key bytes
5. Interpret result as ASCII text

---

## Slate Message Format

Messages delivered as decimal numbers over the phone:

```
[sequence_number] [YYMMDD] start
[decimal values 0-255, space-separated]
End of message. Cheers.
```

**Decryption steps:**
1. Transcribe decimal values
2. Find the row matching the sequence number in *Slate Deposits in the Intermountain West*, appropriate section for the story (301/302/303)
3. XOR each decimal value against the corresponding row value
4. Interpret result as ASCII text

---

## OTP Black Messages (Original Run)

The "OTP Black" codes (agent codes `6871–6879`) were the original run's equivalent of the XORFS system — shorter, status-level encrypted messages. Nine codes (Black 1 through Black 9) with 149 total calls across the range.

These were separate from the main 18xxx message system and appear to have been a status/telemetry layer rather than narrative messages.

---

## Shadow Code Drops (Unsolved)

Mailed packages to some players contain **512-byte random blobs** labeled as "Shadow Code Drops." Their purpose is unknown. They may be:
- Key material for an undiscovered system
- Firmware for the MXP20 processor
- Encrypted messages requiring an unidentified key

See [puzzles/unsolved/index.md](../../puzzles/unsolved/index.md).

---

## Tools

- **OTP XOR Decoder**: https://otp22.org/tools/
- **XOR tool** (drag-and-drop, multiple formats, gzip): https://otp22.org/tools/
- **Slate Deposits decoder**: https://otp22.org/tools/
