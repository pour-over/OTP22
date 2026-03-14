# XORFS — Encrypted Message System

*The primary narrative messaging system of the revival era.*

---

## Overview

**XORFS** is Emtanon's internal texting/messaging system. Messages are found on AS32 in sequential agent code ranges, encrypted with a XOR cipher using a one-time pad key file.

XORFS messages form the main narrative of the revival. Archived messages span from September 2022 to the present, organized in blocks of 50 message slots.

---

## How XORFS Works

### Message Locations on AS32
Messages occupy two ranges:
- `18000–19999` — Primary XORFS range
- `22000–22999` — Secondary XORFS range

Each code contains one message. Messages advance sequentially.

### Message Format
When decoded, each message follows this pattern:

```
Blue OTP 1 file start
[hexadecimal ciphertext as NATO phonetic alphabet]
[offset value for key position]
End of message. Cheers.
```

The "Blue OTP 1" designation refers to the key file: `otp-blue-1.bin`.

### Encryption Method
XOR cipher:

```
plaintext = ciphertext XOR key_fragment
```

Where `key_fragment` is a slice of `otp-blue-1.bin` starting at the specified `offset`.

### The Key File
`otp-blue-1.bin` — approximately **1 GB** of key material.

**Origin:** The El Paso, TX dead drop (December 2012, original run). The file was on the El Paso CD.

This is a true one-time pad: each offset is used only once, making individual messages unbreakable without the key. The key file's large size allows for years of messages.

---

## NATO Phonetic Delivery

The ciphertext is spoken over the phone as hexadecimal bytes using the NATO phonetic alphabet:
- `Alpha` = A
- `Bravo` = B
- `Charlie` = C
- `Delta` = D
- `Echo` = E
- `Foxtrot` = F
- `0–9` = spoken as digits

Community members transcribe these transmissions, convert from NATO phonetic to hex, then XOR against the key to produce plaintext.

---

## Decoding Tools

- **OTP XOR Decoder**: https://otp22.org/tools/ (accepts hex input + key file)
- **XOR tool**: Drag-and-drop, multiple formats, gzip support at otp22.org/tools/

---

## Message Archive

Messages are archived on the otp22.org wiki organized chronologically. The archive spans from September 2022 (pre-revival testing?) through the present.

**Total messages:** Thousands across both code ranges.

Notable message numbers:
- `18001` — First OTP message (original run, Dec 2012): established plot summary
- `18029` — Referenced Rainier OR drop
- `18056` — Bangkok drop reference
- `18054` — Malaysia drop reference
- `18073` — Santa Clara drop reference
- `18087` — NYC drop reference (1)
- `18093` — NYC drop reference (2)
- `18098` — Carlisle PA drop reference
- `18109` — El Cerrito drop reference
- `18114` — Referenced phone number 2723649905
- `18119` — "Black OTP" message mentioning 2723649905
- `18134` — Dimitrovgrad drop reference
- `18141` — Sofia drop reference
- `18349` — J requests red terminal ("green was stupid")
- `18438` — Hints `insurance.bin` contains compromising data on Debra Fisher

---

## Original Run OTP Messages

In the original run, the equivalent system was also on the `18xxx` range but used a different pad. The community tracked 2,897 calls to `18000–18999` codes — by far the most-called range, reflecting the importance of these messages to the narrative.

The original run pads came from physical CDs in dead drops (OTP7, OTP8, OTP9 from Kauai; the North Dakota CD; the El Paso CD; others). Each CD label indicated which pad it contained.

---

## Slate Messages vs XORFS

Slate messages (codes `301/302/303` on AS32) are a related but distinct system:
- Shorter messages
- Encrypted with the *Slate Deposits in the Intermountain West* physical book
- Delivered as decimal numbers (0–255) rather than NATO phonetic hex
- 24-hour broadcast window
- Three "stories" (one per Slate code), each using a different section of the book

See: [slate/index.md](../slate/index.md)
