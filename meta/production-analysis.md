# Production Analysis

*Who built OTP22, how, and at what cost. Analysis of the team and infrastructure.*

---

## The Puppetmaster

**Casey Halverson** (Reddit: u/tanik) is the confirmed creator of OTP22. He has made occasional appearances on r/OTP22 to confirm facts, tease upcoming content, and acknowledge community milestones.

What his involvement suggests:
- Deep knowledge of VoIP telephone infrastructure
- Understanding of IVR design (Asterisk/FreeSWITCH or similar)
- Cryptographic competence (OTP implementation, steganography)
- Long-term creative vision (13+ years of consistent world-building)
- Logistics capability (international dead drop placement)
- Financial resources to sustain a long-running ARG

---

## Team Size Estimate

Based on the scope of work, the team likely includes **3–8 core members** with distributed drop agents. Required skills across the full production:

| Skill Domain | Evidence |
|-------------|----------|
| Telecom engineering (PBX/IVR) | Level 3 DID provisioning, CLLI codes, Bell system conventions, conference bridge architecture, calling card systems |
| Web development | emtanon.com portal, marineorg.com, otp22.org, terminal emulators |
| Audio engineering | Custom audio protocols (ABISM, TAMI, M6, M7), SSTV production, Bell 103 telemetry, voice recordings |
| Cryptography | OTP/XOR implementation, steganography (Steghide), key distribution logistics |
| Graphic design | 200+ ExcitingBooks covers, in-universe document design, book cover printing |
| Narrative writing | 13+ years of consistent lore, 18xxx message archive, character development |
| Physical logistics | International dead drop placement across 7+ countries |
| Voice acting | J (British accent), multiple character voices for phone recordings |
| Music production | Original music on streaming platforms |
| Hardware engineering | MXP20 processor architecture, Gorno32 console, NES cartridge production |
| Operational security | 13 years of identity protection |

Andrew Filer (Troy) was definitively a core team member — creator of ExcitingBooks aesthetic, Message Desk operator.

---

## Infrastructure Cost Estimate

Annual operating costs (conservative estimates):

| Item | Estimated Annual Cost |
|------|-----------------------|
| 7+ VoIP/DID phone numbers (Level 3 wholesale) | $50–200/month = $600–2,400/yr |
| Web hosting (multiple domains + portal with terminals) | $100–500/month = $1,200–6,000/yr |
| PBX/IVR platform (Asterisk/FreeSWITCH hosting) | $200–1,000/month = $2,400–12,000/yr |
| PO Box rental (CMCH NJ) | ~$200/yr |
| Postage for outgoing mail (books, calling cards, letters) | $500–2,000/yr |
| Physical book printing (multiple titles, annual Slate editions) | $1,000–5,000/yr |
| Cleveland Direct calling card printing | $200–1,000/yr |
| Dead drop materials (USB drives, keychains, stickers, NFC tags, containers) | $500–2,000/yr |
| Travel for drop placement (domestic + international) | $2,000–10,000/yr |
| Music production + streaming distribution | $500–2,000/yr |
| Domain registrations (emtanon.com, marineorg.com, etc.) | ~$100/yr |
| **Total estimate** | **$9,000–42,000/yr** |

Original run (2012–2016 × 5 years) + revival (2023–present × 3+ years) = **8+ years of active operation** at these costs.

**Conservative total investment: $70,000–$340,000+**

This does not account for one-time costs (Gorno32 hardware development, NES cartridge production, MXP20 processor design) or the enormous labor cost of thousands of hours of creative and technical work.

---

## Technology Stack Analysis

### Phone Infrastructure
- **Carrier:** Level 3 Communications (now Lumen Technologies) — wholesale DID provisioning
- **Platform:** Almost certainly Asterisk or FreeSWITCH (open-source PBX)
- **IVR scripting:** AGI (Asterisk Gateway Interface) or FreeSWITCH ESL
- **Audio:** Custom TTS voices, recorded character voices, synthesized audio protocols

### Web Infrastructure
- **emtanon.com**: Web server hosting terminal emulators (likely Node.js or similar)
- **Terminal emulators**: Custom WebSocket-based terminal simulation
- **marineorg.com**: Static/CMS site with YouTube integration
- **otp22.org**: MediaWiki installation

### Custom Systems
- **MXP20**: Custom processor architecture (documented but not publicly reverse-engineered)
- **ABISM protocol**: Custom FSK-based modem protocol with hardware device counterpart
- **TAMI, M6, M7**: Additional custom audio protocols
- **Iris messaging**: Custom real-time messaging system accessible via terminals
- **Technoscrip**: Custom cryptocurrency

### Physical Production
- **Books**: Professional print-on-demand or small-run commercial printing
- **Calling cards**: Custom printed prepaid cards
- **USB drives**: Standard consumer hardware
- **NFC tags**: Standard consumer hardware

---

## Operational Security

The team has maintained near-complete anonymity for 13+ years. Public-facing elements:
- Casey Halverson's Reddit account (u/tanik) is the only confirmed identity
- Andrew Filer was known to the community before his death
- Drop agents distributed globally are essentially anonymous

This level of operational security over such a long period is itself remarkable — comparable to some professional intelligence operations in its compartmentalization.

---

## Creative Vision

What makes OTP22 remarkable as a creative work:

1. **Consistency across 13 years** — The aesthetic, tone, and universe have been maintained without drift across a decade-long hiatus and revival.

2. **Integration of real infrastructure** — Real phone numbers, real postal addresses, real geographic coordinates, real technical protocols. The boundary between the game and reality is deliberately blurred.

3. **Andrew Filer's ExcitingBooks** — The aesthetic vocabulary of 200+ fake books is a distinct artistic achievement: encyclopedic knowledge applied with perfect comic deadpan.

4. **Respect for the audience** — The puzzles are genuinely difficult. The cryptography is real. The community that formed around OTP22 developed genuine technical skills in XOR decryption, SSTV reception, ITA2 decoding, and audio protocol analysis.

5. **The physical layer** — Driving to Lake Oswego, OR or flying to Tapiola, Finland to retrieve a container is not a normal ARG experience. The physical dimension creates real stakes and real community.

---

*For the phone phreak/Shadytel community connection hypothesis, see [shadytel-connection.md](shadytel-connection.md).*
