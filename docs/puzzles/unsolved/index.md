# Unsolved Puzzles & Open Threads

*Active mysteries as of documentation date. Contribute findings to otp22.org.*

---

## insurance.bin
**Origin:** El Paso, TX revival drop
**Type:** Binary file
**Status:** Unsolved

A large binary file from the El Paso drop. XORFS message 18438 hints that it contains compromising information about **Debra Fisher**, Chief Finance Manager of Emtanon. The file's format, encryption, and full contents have not been determined.

Known facts:
- Found alongside `otp-blue-1.bin` and the AI portrait JPEGs in the El Paso drop
- Message 18438 is the only explicit in-game reference to its contents
- May require a key from a different source (a physical drop? a Cleveland Direct class-6 number?)

---

## Shadow Code Drops
**Origin:** Mailed packages to players
**Type:** Binary blobs, 512 bytes each
**Status:** Unsolved

Some agent letters mailed to players contain 512-byte binary blobs labeled as "Shadow Code Drops." Their purpose is entirely unknown.

Hypotheses:
- Key material for an undiscovered system
- Firmware or boot code for the MXP20 processor
- Encrypted messages requiring an unidentified key
- Data for the Gorno32 or NES cartridge systems (when they eventually ship)

---

## Agent Code 55559 — "Melter"
**Type:** AS32 agent code behavior
**Status:** Partially understood

Dialing AS32 and entering `55559` says "Melter" and then prompts for input. The prompt accepts data but nothing known has produced a meaningful response.

Hypotheses:
- Accepts MXP20 machine code for upload to MELTR ships
- Accepts some kind of control sequence for Melter fleet operations
- Requires a specific data format from a physical drop

---

## OTP-DAT-05
**Origin:** Agent letters (mailed materials)
**Type:** Binary blobs, 500–600 bytes
**Status:** Unsolved

Unsolved blobs found in the physical book (Slate Deposits or similar). Not yet correlated to any known decryption method or system.

---

## Nashville Drop Numbers
**Origin:** Nashville, TN drop *Slate Deposits* book
**Status:** Unsolved

The Nashville *Slate Deposits* edition contains numbers that are **not accepted by any known system**:
- Not valid Slate message decryption inputs
- Not accepted by Flare Pepper Kitchen
- Not accepted by Path Controller
- Not accepted by AS32 agent codes

The Nashville numbers may be for an entirely separate system, or may require context from another drop that hasn't been found.

---

## Irving Drop MIDI File
**Origin:** Irving, TX drop
**Status:** Partially decoded

A MIDI file where the note arrangement appears to encode a binary data block. The structure is visible — notes are not musical but systematic — but the data block has not been fully interpreted.

Approach: Map notes to bit values, reconstruct byte array, identify file signature or format.

---

## Sunnyvale Blob
**Origin:** Sunnyvale, CA drop
**Status:** Unsolved

Unsolved data from the Sunnyvale drop book. Format unidentified.

---

## Wailua Drop — Route Code, Path, Pass
**Origin:** Wailua, HI drop
**Status:** Unsolved

The Wailua drop contained handwritten:
- Route code
- Path
- Pass

None of these have been accepted by:
- AS32 agent codes
- Path Controller
- Flare Pepper Kitchen
- Any other known system

The Wailua drop also contained an NFC tag connecting to the OVAL terminal. The NFC tag and the handwritten codes may be related — or may be two separate puzzles.

---

## OVAL Terminal — Credentials Unknown
**Status:** Unsolved

The OVAL terminal (newest Emtanon system) requires credentials. No player has obtained working credentials as of documentation date.

The OVAL terminal:
- Runs clones of popular games
- Has a terminal app using Hayes AT command set
- Contains an NFC tag (connected to Wailua drop)
- Credentials possibly in Wailua drop data, or in an undiscovered drop

---

## MXP20 Processor Architecture
**Status:** Partially documented

The Emtanon terminals and MELTR ships run on the custom **MXP20** processor architecture. Agent code `55559` ("Melter") accepts machine code input. No player has successfully uploaded runnable MXP20 code.

For a complete MXP20 writeup see [systems/protocols/other-protocols/index.md](../../systems/protocols/other-protocols/index.md).

---

## Undiscovered Game Systems

The game designers have explicitly stated these systems exist but zero players have discovered them:

| System | Status |
|--------|--------|
| **Shortwave radio transmissions** | 0 received. Requires shortwave receiver + correct frequency knowledge. |
| **Zeus transmissions** | 0 received. Zeus satellite system from original run; unclear revival implementation. |
| **Gorno32 shipments** | 0 shipped. Likely a custom game console. What game does it run? |
| **NES cartridges** | 0 shipped. Actual Nintendo cartridges with custom content. |

These are potentially the largest undiscovered content in the game.

---

## ABISM — Persistent Open Questions
- What is the full modulation scheme?
- Is the ABISM MAPS service (code `1320`) fully decoded?
- What did Robby mean by "ABISM" as a contact channel?
- See full writeup: [systems/protocols/abism/index.md](../../systems/protocols/abism/index.md)

---

## Original Run Loose Threads

### AI Bouerges Disappearance
J's frantic March 2013 message (*"SHE IS NOT HERE. WE ARE ALL WAITING. WHERE IS SHE?"*) about agent 16041 / AI Bouerges was never formally resolved in the original run. Did the revival explain what happened to her?

### Robby's Fate
Robert Bramble's status at the end of the original run is unknown. In the revival he appears to be back at Emtanon in a staff role — reconciliation? Different timeline? His original-run escape and leaked materials remain unexplained in terms of long-term consequences.

### LONGVAULT and IRISLATCH
These named operations from 2013 were never fully explained. What was the outcome of LONGVAULT? Did the Melter fleet reach Svalbard?

### The Svalbard Vault
Did any physical components from the original run's drops actually constitute a "complete set"? Was the assembly at Svalbard ever achieved in the game's fiction?

---

*Submit puzzle progress at https://otp22.org or on r/OTP22.*
