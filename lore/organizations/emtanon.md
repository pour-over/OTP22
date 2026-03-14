# Emtanon Ltd

*"A British logistics corporation." — In-game description*

---

## Overview

**Emtanon Ltd** was established in 1975 by Dr. J Marvin Blackweather. It presents itself as a British logistics company but operates as a criminal front organization conducting covert global operations. In the original run it was referenced obliquely; in the 2023 revival it became the primary institutional face of the game.

Emtanon is characterized by:
- Deliberate retention of 1970s-era technology (as aesthetic and operational security)
- Bureaucratic internal culture with formal procedures and terminology
- A global reach through legitimate-appearing business fronts (weather stations, amusement parks, slot machines)
- Backdoored IoT appliances used for surveillance and sabotage
- An internal telephone agent system (AS32) that has been exploited by players
- Real working web portal with terminal emulators accessible to verified agents

**Website:** https://emtanon.com

---

## Known Operations

### Weather Stations
Emtanon operates weather stations at remote locations. The **Gough Island weather station** in the South Atlantic is a confirmed front — it's where Felicity Love worked as an intern and discovered the criminal operations.

### Amusement Parks
Referenced in internal documents. Details sparse.

### Slot Machines
Referenced in internal documents. Possible surveillance or financial infrastructure.

### Backdoored IoT Appliances
WORM's "Project MLPL" exploits backdoored Emtanon IoT devices to trigger power blackouts.

---

## Physical Locations

| Location | Designation | Notes |
|----------|-------------|-------|
| The Rock (Gibraltar) | Emtanon HQ | Green Terminal (Room 101), Amber Terminal (Room 104), Red Terminal (J's) |
| Hilo, Hawaii | Pacific Command | Aqua Terminal; taken offline Feb 21, 2024, restored June 7, 2024 |
| Gough Island | South Atlantic Weather Station | Site of Gough Ceremony (Sept 24, 2023); training facility |
| Bouvet Island | Subantarctic Outpost | North Korean missiles acquired Jan 2024; construction since March 2024 |
| Leskov Island | South Atlantic | Referenced in SHIP messages |
| Exeter, UK | UK HQ | |
| Iqaluit, Canada | Field Office | Phone: +1 (867) 794-0033 |
| CMCH, NJ | Field Agent Coordinator | Debbie Wright; PO Box for postal operations |
| Liberty, KY | ITOPS | Robert Bramble's base; AS32 management |

---

## Personnel (Revival Era)

| Name | Role | Contact |
|------|------|---------|
| Dr. J Marvin Blackweather | Founder/Head | — |
| Esprit Boursicot | HQ Operations, terminal supervisor | Iris: 16001; Green Terminal: 16009 |
| Desiree Martin | Senior Project Manager, Gough Island | Iris: 17001 |
| Robert "Robby" Bramble | ITOPS, AS32 management, Liberty KY | — |
| Maria Peters | Computer Security | — |
| Debbie Wright | Field Agent Coordinator, CMCH NJ | — |
| Debra Fisher | Chief Finance Manager | — |
| Tala Torres | J's companion | — |

---

## The Agent System (AS32)

The agent system `+1-606-722-0004` (AS32) is Emtanon's primary internal communication infrastructure for field agents. It is an IVR system that responds to DTMF input with messages, data, and encrypted transmissions.

Key AS32 agent codes:
- `1` — Telemetry
- `2` — Bell 103 telemetry
- `3#` — Green terminal SSTV
- `10#` — Amber terminal SSTV
- `11#` — Red terminal SSTV
- `301/302/303` — Slate messages (OTP-encrypted short texts)
- `16000` — Friendly code verifier
- `16001–16999` — Agent management
- `18000–19999` — XORFS messages
- `22000–22999` — XORFS messages (continued)
- `6824418` — Message Desk (Troy/Andrew Filer)
- `238018300–238018399` — SSTV range

Full agent code database: [systems/agent-codes/index.md](../../systems/agent-codes/index.md)

---

## Emtanon Portal

The Emtanon portal at emtanon.com hosts real web-based terminal emulators simulating 1980s-era text terminals. Access requires credentials obtainable via postal mail (Access Request form AC-P-REQ-01 sent to the CMCH NJ PO Box).

Terminals accessible via portal:
- **Green Terminal** (Gibraltar Room 101)
- **Amber Terminal** (Gibraltar Room 104)
- **Red Terminal** (J's personal terminal)
- **Aqua Terminal** (Hilo, Hawaii)
- **OVAL Terminal** (newest system)
- **Path Controller**

See: [systems/terminals/index.md](../../systems/terminals/index.md) and [systems/web/emtanon-portal/index.md](../../systems/web/emtanon-portal/index.md)

---

## The Iris Messaging System

Emtanon's internal real-time messaging platform. Accessible from all terminals and mobile units. Talk groups are numeric (negative = mobile).

Known Iris groups:
| Group | Identity |
|-------|----------|
| 0 | ITOPS |
| 1 | HQ |
| 100 | MO1 |
| 112 | AIR1 |
| 201 | MO5 |
| 211 | AIR2 |
| 291 | MO2 |
| 284 | Material Order Desk |
| 411 | Directory Assistance |
| 555 | MO5 |
| 609 | MO6 Bridge |
| 660 | Shadow Team |
| 808 | Honolulu Tape Retrieval |
| 15034 | Debra Fisher |
| 16001 | Esprit Boursicot |
| 16009 | The Rock Room 101 / Green Terminal |
| 16921 | The Rock Room 104 / Amber Terminal |
| 17001 | Desiree Martin |
| 19001 | Hilo Room 101 / Aqua Terminal |

---

## Technoscrip

Emtanon's internal cryptocurrency. Balance checkable via the agent management system on AS32.

---

## Original Run Presence

In the original run (2012–2016), "Emtanon" appeared as a vendor/contractor referenced in internal messages — typically blamed for software issues with AS36 ("Alpha Sigma 36," the remote field installation). The full Emtanon organization was not yet the central frame; that came with the 2023 revival.

Agent code `0096001` on the original run system was labeled "Emtanon" (17 calls logged).

---

*See also: [Marine Org](marine-org.md) | [WORM / MLPL](worm-mlpl.md)*
