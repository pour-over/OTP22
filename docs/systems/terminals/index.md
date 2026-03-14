# Terminals

*1980s-era text-only computer terminals throughout the Emtanon organization. Accessible via the Emtanon web portal (emtanon.com) and via SSTV audio transmissions on AS32.*

---

## Overview

Emtanon deliberately retains obsolete 1970s–80s era technology. The terminals are simulations of this aesthetic: text-only, command-line interfaces with constrained command sets. In the revival, they are real web-based terminal emulators accessible through the emtanon.com portal.

Terminal access requires credentials. These can be obtained by mailing the Access Request form `AC-P-REQ-01` to the CMCH NJ PO Box.

---

## Terminal Inventory

### Green Terminal
**Location:** The Rock (Gibraltar), Room 101
**User:** Esprit Boursicot
**Iris group:** `16009`
**SSTV:** AS32 code `3#`

The primary HQ terminal. Boursicot uses it to supervise operations and test system functions. Runs with sysop privileges — unique commands and programs not available on other terminals. One of the two original Rock terminals.

### Amber Terminal
**Location:** The Rock (Gibraltar), Room 104
**Iris group:** `16921`
**SSTV:** AS32 code `10#`

Auxiliary terminal for visitors. Slightly older software than Green. On August 8, 2023 it was discovered to run Unix programs and support Steghide encryption — a significant capability discovery. Used for steganographic operations.

### Red Terminal
**Location:** The Rock (Gibraltar) — J's personal workspace
**SSTV:** AS32 code `11#`

J requested a red terminal because green was "stupid" (referenced in message 18349). Personal to J; not typically accessible by field agents.

### Aqua Terminal
**Location:** Hilo, Hawaii (Pacific Command), Room 101
**Iris group:** `19001`

Key role in Operation Spice planning and the FACILITY Redemption. AIR1 and MO5 took it **offline on February 21, 2024** to hide evidence from the Operation Spice fallout. Restored **June 7, 2024**.

### Path Controller
**Location:** Network-accessible (not physically tied to one location)

Controls **semaphores** — data registers that govern Emtanon physical systems including ship remote control and scuttling. Password-protected.

The key is provided via Felicity Love's voicemail system and player mailings as XOR byte strings. This is how players assisted the FACILITY Redemption:

```
Cell locks: 0xFF → 0x00  (all cells unlocked)
```

### OVAL Terminal
**Location:** Newest addition to the system
**Notes:** Runs clones of popular games plus a terminal app using the Hayes AT command set. Contains an NFC tag from the Wailua drop. Credentials unknown to players as of documentation date.

---

## Terminal Commands

Commands available on all standard terminals:

| Command | Function |
|---------|----------|
| `help` | Show available commands |
| `list [+all]` | List files/programs |
| `make` | Create something |
| `open` | Open a file |
| `return` | Return to previous context |
| `where` | Show current location |
| `delete` | Delete a file |
| `create` | Create a file |
| `read` | Read a file |
| `write` | Write to a file |
| `clear` | Clear screen |
| `beep` | Beep |
| `play <ms> <hz> <vol> <waveform>` | Play audio tone. Waveforms: `square`, `sine`, `triangle`, `sawtooth` |
| `run <name> <args>` | Run a program |

### Undocumented / Sysop Commands

| Command | Function |
|---------|----------|
| `export` | Sysop only — uploads to agent systems |
| `line` | Undocumented |
| `ohio <pin>` | Cleveland Direct card activation |
| `plot` | Undocumented |
| `reboot` | Reboot the terminal |
| `run free` | Freeform input mode |
| `sabre airport arrived/inbound/outbound <airport>` | SABRE airline reservation system interface |

### Terminal Programs

| Program | Function |
|---------|----------|
| `as27` | Terminal program for AS27 agent system |
| `iris` | Iris messaging client |

---

## Accessing via SSTV

Before the web portal existed (and still periodically), terminals broadcast their screen contents via **SSTV** (Slow-Scan Television) on the AS32 agent system. Callers could receive an image of the terminal's current state.

| Terminal | AS32 Code |
|----------|-----------|
| Green | `3#` |
| Amber | `10#` |
| Red | `11#` |

Additional SSTV codes: `238018300–238018399` (range), `891038117–118`.

---

## MXP20 Processor

The terminals and potentially the MELTR ships run on the **MXP20** custom processor architecture. Machine code can be uploaded to the system via AS32 (see agent code `55559` — "Melter" — which prompts for input after the machine code context).

This is an unsolved area of the game. See [puzzles/unsolved/index.md](../../puzzles/unsolved/index.md).
