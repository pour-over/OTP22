# Revival Dead Drops (2023–present)

*17+ confirmed drops as of documentation date. 2 incomplete.*
*Source: otp22.org wiki.*

---

## Overview

The revival-era drops are geocaching-style containers hidden in public and semi-public spaces. Coordinates are delivered through the AS32 agent system, Felicity Love's accounts, and other channels. Contents have evolved from the original run: USB drives have largely replaced CDs, NFC tags have been added, and the *Slate Deposits in the Intermountain West* book is standard issue.

Postal mail to the CMCH NJ PO Box can supplement physical drop retrieval — many book and calling card distributions happen via mail rather than physical drops.

---

## Confirmed Drops

| Location | Country | Status | Notable Contents |
|----------|---------|--------|-----------------|
| Cape May, NJ | USA | Retrieved | First revival drop; near the CMCH NJ PO Box |
| El Paso, TX | USA | Retrieved | `otp-blue-1.bin` (~1 GB key file); AI-generated portrait JPEGs with steghide data; `insurance.bin` |
| Pawnee Rock, KS | USA | Retrieved | — |
| Federal Way, WA | USA | Retrieved | — |
| Riverside, IA | USA | Retrieved | Jeff A.'s hometown; related to his character |
| Calgary, AB | Canada | Retrieved | — |
| Tuktoyaktuk, NT | Canada | Retrieved | Far north; one of the most remote drops |
| Las Vegas, NV | USA | Retrieved | *Slate Deposits in the Intermountain West* (2024 edition) |
| Ruston, WA | USA | Retrieved | Message Desk code (`6824418`) rediscovered here; *Slate Deposits* (2024) |
| Macau | China (SAR) | Retrieved | International drop |
| Nashville, TN | USA | Retrieved | *Slate Deposits* book with anomalous numbers (unsolved) |
| Gatlinburg, TN | USA | Retrieved | — |
| Irving, TX | USA | Retrieved | MIDI file with binary-encoded data |
| Edgewood, WA | USA | Retrieved | *Slate Deposits* (2025 edition) |
| Sunnyvale, CA | USA | Retrieved | Blob with unsolved data |
| Wailua, HI | USA | Retrieved | *Slate Deposits* (2025); NFC tag; handwritten Route code, path, pass |
| Hot Springs, AR | USA | **Incomplete** | Not yet retrieved/confirmed |
| Slide Cemetery, AK | USA | **Incomplete** | Not yet retrieved/confirmed |

---

## El Paso Drop — Key Artifacts

The El Paso TX revival drop is the most technically significant:

### otp-blue-1.bin
~1 GB file. The one-time pad key used for all XORFS messages on AS32 codes `18000–19999` and `22000–22999`. Every XORFS message since the revival began is decryptable with this file.

### AI-Generated Portrait JPEGs
Five JPEGs of AI-generated human faces, named:
- `David_1.jpg`
- `Jose_1.jpg`
- `Maria_1.jpg`
- `Matt_1.jpg`
- `Tim_1.jpg`

Each contains steganographic data embedded with **Steghide**. The Maria_1.jpg yielded friendly code: `55 29 54 88 84 46 06 26` (verified at AS32 code `16000`).

### insurance.bin
Large binary file. Message 18438 hints it contains "dirt" on **Debra Fisher**, Chief Finance Manager. Unsolved. See [puzzles/unsolved/index.md](../../puzzles/unsolved/index.md).

### weirdblock.bin / elcerrito.bin equivalents
The original run El Paso drop also had a `weirdblock.bin` "hole" — the revival drop appears to continue this pattern with `insurance.bin`.

---

## Ruston, WA Drop — Message Desk Rediscovery

The Ruston drop book contained an agent code that led players to `6824418` on AS32 — **the Message Desk**, originally operated by Andrew Filer (Troy). This rediscovery on January 7, 2024 was a significant community moment.

---

## Wailua, HI Drop — NFC Tag

The Wailua drop contained a physical NFC tag that connects to the OVAL terminal system. The OVAL terminal contains an NFC tag program. The drop also included handwritten:
- Route code
- Path
- Pass

These have not been accepted by any known system. Open puzzle.

---

## Irving, TX Drop — MIDI File

The Irving drop contained a MIDI file with notes arranged as a binary data block. The data has not been fully decoded. Open puzzle.

---

## Standard Drop Contents

Most revival drops include some combination of:
- Physical copy of *Slate Deposits in the Intermountain West* (current edition)
- USB drive with digital content
- Stickers (Emtanon/WORM aesthetic)
- Keychains
- Agent letter with encoded data (sometimes containing 512-byte "Shadow Code" blobs)
- Friendly codes for verification at AS32 code `16000`

---

## Postal Mail Distributions

Many game items are distributed via postal mail rather than physical drops:
- *Slate Deposits in the Intermountain West* (can be mail-ordered)
- Cleveland Direct calling cards
- Agent letters with encoded data and Shadow Code blobs
- Portal access credentials (form `AC-P-REQ-01`)

Mail: **DROP AGENT CATALOG, 615 US-9 S #172, CMCH, NJ 08210**

---

## Unrevealed Systems

The game designers have indicated these systems exist but no player has discovered them:

| System | Status |
|--------|--------|
| Shortwave radio transmissions | 0 received |
| Zeus transmissions | 0 received |
| Gorno32 shipments | 0 shipped |
| NES cartridges | 0 shipped |

These represent potentially major undiscovered content.
