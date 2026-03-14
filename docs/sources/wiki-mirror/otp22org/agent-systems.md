# Agent Systems — otp22.org Wiki Mirror

**Source:** https://otp22.org/doku.php?id=agent_systems

Agent systems are phone numbers for WORM agents, used to receive and send messages while in the field. Most take the form of interactive voice response (IVR) menus.

---

## AS27

**Phone number:** +1-207-813-2200
**Detailed page:** https://otp22.org/doku.php?id=as27
**Monthly archives:** https://otp22.org/doku.php?id=start&idx=as27

AS27 broadcasts a **single message for 24 hours**, starting at 00:00 UTC. Used for organization announcements and occasional messages from assets.

**Audio samples:**
- [as27.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:as27.flac) — Typical AS27 call
- [as27-0000.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:as27-0000.flac) — "0 0 0 0" empty message

### AS27 Message Format

```
[Sequence]: [Authority] [Text]
```

- **Sequence:** Two numbers separated by "point"
  - First number: Years since 1975 (Emtanon founding year)
  - Second number: Day of the year, counting from zero
- **Message authority:** Meaning unknown. Has been "98" since the revival began.
- **Text:** Plain English organizational directive

### AS27 Monthly Archives (Revival)

| Year | Months Archived |
|------|----------------|
| 2023 | May, June, July, August, November, December |
| 2024 | January–December (all 12) |
| 2025 | January–December (all 12) |
| 2026 | January, February (ongoing) |

**Original-run connection:** The original AS27 was at 7208970004 (discovered by appending 0004 to partial number `720 897` overheard in a conference call recording). The revival AS27 continues the same format.

---

## AS32

**Phone number:** +1-606-722-0004
**Page:** (stub — no dedicated wiki page yet)

AS32 provides access to agent codes. Its main purpose is serving Slate, XORFS, and SSTV messages, but it also has various hidden functions.

**Audio:** [as32.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:as32.flac) — AS32 welcome prompt

### Key Agent Codes on AS32

| Code | Function |
|------|----------|
| `1` | Telemetry |
| `2` | Telemetry (Bell 103 modem) |
| `3` | Green terminal (SSTV) |
| `10` | Amber terminal (SSTV) |
| `11` | Red terminal (SSTV) |
| `301`, `302`, `303` | Slate messages (24h broadcast each) |
| `16000` | Friendly code verifier |
| `16001`–`16999` | Agent management system |
| `18000`–`19999` | XORFS messages |
| `22000`–`22999` | XORFS messages (continued) |
| `6824418` | Message Desk (operated by real person) |
| `238018300`–`238018399` | SSTV image gallery |

---

## Cleveland Direct

**Phone number:** +1-412-888-0004

This system provides access to **class 6 telephone numbers**, which aren't callable from regular telephones. A PIN from a Cleveland Direct calling card (obtainable via postal mail) is required before dialing.

Like real-world calling cards, they have a **limited number of minutes**.

**Audio:** [cd.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:cd.flac) — CD welcome prompt

**Images:**
- [cdfront.jpg](https://otp22.org/lib/exe/detail.php?id=agent_systems&media=agent_systems:cdfront.jpg) — 2023 calling card (front)
- [cdback.jpg](https://otp22.org/lib/exe/detail.php?id=agent_systems&media=agent_systems:cdback.jpg) — 2023 calling card (back)

**Official video:** https://www.youtube.com/watch?v=pVVU7-ZPHjc

**How to obtain a card:** Send postal mail to the CMCH, NJ PO box requesting a "CD" — see [postal mail](special-content.md#postal-mail).

**Original-run connection:** The original Cleveland Direct was at 4128880004 — same number format, same function.

---

## Flare Pepper Kitchen (FPK)

**Phone number:** +1-216-677-0004
**Detailed page:** https://otp22.org/doku.php?id=flare_pepper_kitchen
**FPK data mode:** https://otp22.org/doku.php?id=fpk_data_mode
**Revealed:** February 2024, in the [Macau drop](dead-drops.md#macau-drop)

**Audio:** [fpk.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:fpk.flac) — FPK welcome prompt

FPK presents itself as a restaurant, but its actual function is **file sharing**. The initial prompt only announces options for food orders and status checks; however, other DTMF inputs lead to hidden functions.

### Menu Options

| DTMF | Surface meaning | Actual function |
|------|----------------|-----------------|
| Standard options | Make/check food orders | Cover story |
| Hidden options | — | File sharing, agent functions |
| `8` | — | **FPK data mode** (AFSK modem) |

### FPK Data Mode (Option 8)

FPK uses **binary audio frequency-shift keying (AFSK)** for data transmission:

| Parameter | Value |
|-----------|-------|
| Symbol rate | 300 Bd |
| Space (0) frequency | 1270 Hz |
| Mark (1) frequency | 1070 Hz |

Packet structure includes info packets and data packets with file descriptors. Full reverse-engineered spec: https://otp22.org/doku.php?id=fpk_data_mode

---

## Honolulu Tape Retrieval System (HTRS)

**Phone number:** +1-808-400-8484

**Audio:** [htrs.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:htrs.flac) — HTRS welcome prompt

This system provides access to reel-to-reel tapes containing **training materials for WORM agents**. Audio quality degrades over time, until the tape head is cleaned using tape `99999`. Newest tapes are announced on tape `0`.

**Full archive:** https://otp22.org/files/htrs/

*Note: Iris talk group `808` is the Honolulu Tape Retrieval System.*

---

## +1-856-666-0004

An additional agent system number documented but not yet fully detailed on the wiki.

---

## Other Phone Numbers

Additional phone numbers exist but are not yet fully catalogued in the revival wiki. The original-run had dozens of numbers; the revival era has introduced new ones through dead drops and agent code discoveries.
