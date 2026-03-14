# Slate Messages

*Short OTP-encrypted broadcasts on AS32 codes 301, 302, and 303.*

---

## Overview

Slate messages are short texts broadcast on AS32 at agent codes `301`, `302`, and `303`. Each message is available for approximately 24 hours before being replaced. They are encrypted with a XOR cipher using the physical book **"Slate Deposits in the Intermountain West"** as the one-time pad.

---

## Format

When a caller dials AS32 and enters a Slate code, they hear:

```
Sequence number [YYMMDD] start
[decimal numbers 0–255, space-separated]
End of message. Cheers.
```

**Example sequence number format:** `247 231204 start` = sequence 247, date December 4, 2023.

---

## The Three Stories

Each Slate code corresponds to a different "story" — a different narrative thread — using a different section of the *Slate Deposits* book as the key:

| Code | Story | Key Section |
|------|-------|-------------|
| `301` | Story A | Section 1 of *Slate Deposits* |
| `302` | Story B | Section 2 of *Slate Deposits* |
| `303` | Story C | Section 3 of *Slate Deposits* |

---

## Decryption Method

1. Call AS32, enter `301`, `302`, or `303`
2. Transcribe the decimal sequence
3. Open your copy of *Slate Deposits in the Intermountain West* to the appropriate section
4. Find the row corresponding to the sequence number
5. XOR each decimal value against the corresponding byte in the book's pad row
6. Convert resulting values to ASCII

The book contains 365 numbered rows of 32 numbers each, in three sections — one row per day of the year, allowing for daily message rotation.

---

## Slate Deposits in the Intermountain West

**Physical book.** New edition distributed annually. Found in multiple drops:
- Las Vegas, NV drop (2024 edition)
- Ruston, WA drop (2024)
- Nashville, TN drop (2024)
- Edgewood, WA drop (2025)
- Sunnyvale, CA drop (2025)
- Wailua, HI drop (2025)

Available via postal mail order from the CMCH NJ PO Box.

Book specifications:
- Author: Jefferson School of Mines (listed)
- 365 rows × 32 numbers per row × 3 sections
- Annual editions with new pad data
- Mid-century ExcitingBooks aesthetic cover design

---

## Decoding Tool

**Slate Deposits decoder:** https://otp22.org/tools/

Accepts the decimal sequence and a photographed/digitized copy of the relevant book row.

---

## Archive

Slate messages are archived on otp22.org from January 2024 onward. Earlier messages were not systematically archived (the format existed from the revival launch but wasn't well-documented until late 2023).

---

## Nashville Drop Anomaly

The Nashville, TN drop (2024) contained a *Slate Deposits* book with numbers that were **not accepted by any known decryption method**. The numbers in the Nashville book don't match any identified Slate code response, Flare Pepper Kitchen input, or Path Controller format.

This is an open puzzle. See [puzzles/unsolved/index.md](../../puzzles/unsolved/index.md).
