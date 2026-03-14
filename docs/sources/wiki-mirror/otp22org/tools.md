# Tools — otp22.org Wiki Mirror

**Source:** https://otp22.org/doku.php?id=tools

Community-hosted tools for decoding messages and following in-world events.

---

## Ship Tracker Visualizer

**URL:** https://otp22.org/tools/ships.html

Paste decoded AS32 ship coordinates to get a visual map of all vessels. Useful for tracking the current positions of the Marine Org fleet.

---

## OTP XOR Decoder

**URL:** https://otp22.org/tools/otpxor.php

A tool to decode XORFS messages. Usage:
1. Paste a string of space-separated numbers (NATO phonetic alphabet decoded to hex)
2. Enter the offset (byte position in the OTP file)
3. Select the proper OTP file (`otp-blue-1.bin`)

**OTP file download:** https://otp22.org/files/elpaso/trash_files/otp-blue-1.bin (1 GB)

---

## Slate Deposits Decoder

**URL:** https://otp22.org/tools/slatexor.html

Tool to decode [Slate messages](messages.md#slate-messages) found on AS32 codes 301, 302, 303.

---

## XOR Tool

**URL:** https://otp22.org/tools/xor.html

General-purpose XOR tool supporting:
- Multiple input formats
- gzip support
- Other data manipulation functions

---

## JSay

**URL:** https://otp22.org/tools/jsay.html

J's greatest hits — an archive of memorable quotes and audio from Dr. J Marvin Blackweather.

---

## File Repository

**URL:** https://otp22.org/files/

Archives of files recovered from dead drops, HTRS tapes, and other sources.

**Key directories:**
- `/files/elpaso/` — El Paso drop files (including `otp-blue-1.bin`, steganography images)
- `/files/elpaso/trash_files/otp-blue-1.bin` — 1 GB OTP key file
- `/files/htrs/` — Honolulu Tape Retrieval System recordings archive

---

## Steganography

**Source:** https://otp22.org/doku.php?id=steganography

Some files from the **El Paso drop** contain hidden information encoded with `steghide`. The El Paso drop contained 8 JPG images (David_1.jpg, Jose_1.jpg, Maria_1.jpg through Maria_4.jpg, Matt_1.jpg, Tim_1.jpg) — several have steganographic content.

### Getting Steghide

- **Windows/Linux:** https://steghide.sourceforge.net/
- **Mac:** Available via Homebrew: `brew install steghide`

### Usage

```bash
steghide extract -sf image.jpg
# Enter passphrase when prompted
```

**Known encoded files:** Maria_1.jpg (confirmed — example shown on wiki page)

---

## Community Tools (Discord)

Additional scripts and tools are shared in the Discord community (https://discord.gg/cPDMFbzVZv), including:
- XORFS batch decoders
- AS27 sequence calculators
- SSTV capture utilities
