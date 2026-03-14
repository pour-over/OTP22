# OTP22 Archive

The definitive knowledge repository for **OTP22** — one of the most technically ambitious alternate reality games ever created. Running since 2011, temporarily dormant 2016–2023, and relaunched May 2023.

---

## What is OTP22?

OTP22 began on November 12, 2011 when a user posted about a mysterious phone number — **303-309-0004** — on the GodlikeProductions conspiracy forum. Calling it revealed encoded messages, DTMF-controlled agent code trees, and eventually: coordinates to physical dead drops scattered across the globe.

Over the next thirteen years it grew into something extraordinary: a hand-crafted universe with real telephone infrastructure, physical objects hidden on six continents, one-time pad cryptography, custom audio encoding protocols, working terminal emulators, an in-universe cryptocurrency, actual printed books, calling cards, postal mail, steganographic JPEGs, and an evolving narrative delivered across thousands of encrypted phone messages.

The game is the work of **Casey Halverson** (Reddit: u/tanik) and collaborators — almost certainly rooted in the Pacific Northwest phone phreaking and hacker scene. Its telephone infrastructure depth (Level 3 Communications DIDs, CLLI codes, Bell system conventions, calling card systems) is unlike anything else in ARG history.

---

## Repository Structure

```
otp22-archive/
├── README.md                        ← You are here
├── TIMELINE.md                      ← Full chronological timeline 2011–present
├── ANDREW_FILER_MEMORIAL.md         ← Tribute to Troy / Andrew Filer (RIP)
│
├── lore/
│   ├── characters/index.md          ← All character profiles
│   ├── organizations/               ← Emtanon, Marine Org, WORM/MLPL
│   ├── events/index.md              ← Major in-game events
│   ├── places/index.md              ← Locations with coordinates
│   └── narrative-timeline.md        ← Story beats in order
│
├── systems/
│   ├── phone-numbers/               ← All known numbers (original + revival)
│   ├── agent-codes/index.md         ← Complete DTMF code database
│   ├── terminals/index.md           ← Green, Amber, Red, Aqua, OVAL terminals
│   ├── messaging/                   ← XORFS, Iris, Slate, AS27, Message Desk
│   ├── protocols/                   ← ABISM, TAMI, M6, M7, SSTV, OTP-XOR, MXP20
│   └── web/                         ← emtanon.com, marineorg.com portal docs
│
├── drops/
│   ├── original-run/index.md        ← 2012–2016: ~50 drops, 44 recovered
│   ├── revival/index.md             ← 2023+: 17+ drops documented
│   ├── drawbars-collection/         ← drawbars' personal artifacts
│   └── coordinates-map.md          ← All drop coordinates
│
├── books/
│   ├── physical-books/index.md      ← Real printed books found in drops
│   ├── exciting-books/catalog.md    ← 200+ absurdist fake book covers by Andrew Filer
│   └── slate-deposits/index.md     ← Annual one-time-pad books
│
├── puzzles/
│   ├── solved/index.md
│   ├── partially-solved/index.md
│   ├── unsolved/index.md            ← Open threads and unsolved data
│   └── techniques.md               ← Decoding guide (XOR, steghide, ABISM, etc.)
│
├── meta/
│   ├── production-analysis.md       ← Who built this and how
│   ├── shadytel-connection.md       ← Phone phreak community hypothesis
│   ├── cost-analysis.md            ← Estimated infrastructure costs
│   ├── technology-stack.md         ← Technical systems analysis
│   └── community-history.md        ← History of the player community
│
├── raw-data/
│   ├── phone-logs/                  ← Agent code call logs and transcripts
│   └── archives/                   ← Archived web content, forum posts
│
└── sources/
    ├── wiki-mirror/                 ← Content from otp22.org wiki
    └── external-references.md      ← All external source links
```

---

## Quick Reference

### Active Phone Numbers (2023+ Revival)
| Number | System |
|--------|--------|
| +1-606-722-0004 | AS32 — Primary agent system |
| +1-207-813-2200 | AS27 — Broadcast announcements |
| +1-412-888-0004 | Cleveland Direct — Calling card system |
| +1-216-677-0004 | Flare Pepper Kitchen — Data transfer |
| +1-808-400-8484 | Honolulu Tape Retrieval System |
| +1-856-666-0004 | Mystery system |
| +1-867-794-0004 | AS33 (mirror) |
| +1-867-794-0033 | HQ (mirror) / Iqaluit field office |

### Original Run Primary Number
**303-309-0004** — First appeared November 12, 2011

### Postal Mail
**DROP AGENT CATALOG**
615 US-9 S #172
CMCH, NJ 08210
(~$20 donation encouraged)

### Online Resources
- **Wiki**: https://otp22.org
- **Tools**: https://otp22.org/tools/
- **In-game site**: https://emtanon.com
- **Marine Org**: https://marineorg.com
- **Community**: r/OTP22

---

## The Two Eras

### Original Run (2011–2016)
The game ran on a network of Level 3 Communications phone numbers, primarily `303-309-0004`. Physical drops were placed across the USA, Finland, Japan, Thailand, Malaysia, Bulgaria, and Australia. ~50 drops, 44 recovered. The game went dark in 2016.

### Revival (May 2023–present)
Relaunched with significantly expanded infrastructure: web terminals at emtanon.com, new in-universe organizations (Marine Org, WORM), new characters (Felicity Love, The Edge, Maria Peters), and an ongoing narrative involving Arctic operations, a prison ship mutiny, and multiple active dead drops.

---

## This Repository

**Primary compiler:** drawbars — original-run player (2012–2016), holder of the Sebastopol drop Cleveland Direct calling card (Oct 2013) and Rohnert Park AS36 functional test printouts (Mar 2014).

This archive is built from:
- The 303.sashahart.net community database (original run research wiki)
- The otp22.org wiki (current community wiki)
- First-hand player knowledge and physical artifacts
- Analysis of all documented messages, drops, and game systems

**Guiding principles:**
1. Completeness over brevity — document everything
2. Preserve primary sources — mirror content, archive links
3. Credit the creators — this is a decade-spanning work of art
4. Respect active players — note where content may spoil undiscovered systems
5. Technical accuracy — document protocols and cryptography with precision

---

*This repository honors the memory of **Andrew Filer** (Troy), Message Desk operator and creator of the ExcitingBooks aesthetic, without whom OTP22 would not be what it is. See [ANDREW_FILER_MEMORIAL.md](ANDREW_FILER_MEMORIAL.md).*
