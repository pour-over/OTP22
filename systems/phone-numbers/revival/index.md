# Phone Numbers — Revival (2023–present)

---

## Active Numbers

### +1-606-722-0004 — AS32 (Primary)
The main agent system for the revival. Accepts DTMF input and routes to hundreds of agent codes.

**Key agent codes on AS32:**

| Code | Function |
|------|----------|
| `1` | Telemetry |
| `2` | Bell 103 telemetry |
| `3#` | Green terminal SSTV |
| `10#` | Amber terminal SSTV |
| `11#` | Red terminal SSTV |
| `301` | Slate message (story A) |
| `302` | Slate message (story B) |
| `303` | Slate message (story C) |
| `16000` | Friendly code verifier |
| `16001–16999` | Agent management |
| `18000–19999` | XORFS messages |
| `22000–22999` | XORFS messages (continued) |
| `6824418` | Message Desk (Andrew Filer / Troy) |
| `238018300–238018399` | SSTV image range |
| `55559` | "Melter" — prompts for input (MXP20 machine code upload?) |

For the complete agent code database, see [systems/agent-codes/index.md](../../agent-codes/index.md).

### +1-207-813-2200 — AS27
Broadcast announcements for the organization. Speaks long sequences of numbers interpretable as ASCII codes. Organizational directives.

### +1-412-888-0004 — Cleveland Direct
Calling card system for "class six" telephone numbers. Requires a PIN from a physical Cleveland Direct calling card. Cards obtainable via postal mail to the CMCH NJ PO Box. The `ohio <pin>` command on the OVAL terminal can also activate a card.

### +1-216-677-0004 — Flare Pepper Kitchen
A data transfer system disguised as a restaurant phone line. Menu options:
- `3/4` — Set baud rate and packet size
- `8` — Receive file transfers

### +1-808-400-8484 — Honolulu Tape Retrieval System
Provides access to reel-to-reel tape recordings for WORM agent training. Code `99999` cleans the tape head. Iris group `808`.

### +1-856-666-0004 — Mystery System
Contains chiptune music and disguised data. Purpose not fully understood.

### +1-867-794-0004 — AS33
Mirror of AS32. Based in Iqaluit, Canada area code.

### +1-867-794-0033 — HQ Mirror / Iqaluit Field Office
HQ mirror line. Also the listed phone number for the Iqaluit field office.

---

## Access Request

To obtain portal credentials, Cleveland Direct calling card, or other materials:

**Mail to:**
```
DROP AGENT CATALOG
615 US-9 S #172
CMCH, NJ 08210
```

**Forms:**
- `AC-P-REQ-01` — Portal Access Request
- Literature Request — for physical books
- ~$20 donation to defray costs

---

## Continuity from Original Run

The original `412-888-0004` (Cleveland Direct/Hampton, Level 3) is mirrored in the revival's `+1-412-888-0004` — the same area code (Pittsburgh), same last four digits. This is a deliberate design choice maintaining continuity across a decade.

The original AS27 was `720-897-0004` (Level 3). The revival AS27 is `207-813-2200` — different carrier, different structure, but same function.

The revival's AS32 at `606-722-0004` replaces the original West/Frederica `303-309-0004` as the primary IVR entry point.
