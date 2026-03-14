# Agent Code Database

Agent codes are DTMF sequences entered after dialing an agent system number. They unlock different content: system messages, encrypted data, audio protocols, conference bridges, and more.

*Primary source for original run data: 303.sashahart.net. Revival data: otp22.org.*

---

## How Agent Codes Work

1. Dial an agent system number (e.g., `+1-606-722-0004`)
2. After the system answers, enter the agent code via DTMF keypad
3. The system responds with audio content appropriate to that code

Code ranges are structured into functional namespaces. The architecture suggests a well-designed IVR platform (likely Asterisk or FreeSWITCH).

---

## Complete Code Table — Original Run

*Call counts from 303.sashahart.net (reflecting community activity through ~2015)*

| Code | Label | Description | Calls |
|------|-------|-------------|-------|
| `*` | — | Grover Cleveland March | 37 |
| `**` | ABISM | ABISM modem signal | 14 |
| `0` | RADIO TEST | Bandwidth frequency test (changed several times over the run) | 781 |
| `1` | — | "One is not a valid selection. Goodbye." | 35 |
| `2` | — | Random snippets from a book about U-boat warfare | 33 |
| `3` | — | "You will never understand us. How beautiful we are. Yeyuh. Why you cut our Forever Beautiful?" | 26 |
| `4` | — | Lists other phone numbers | 41 |
| `5` | — | "How beautiful we are." | 17 |
| `6` | — | "She's not into you she's into the idea of" | 11 |
| `7` | — | "XOR XOR XOR XOR XOR XOR XOR XOR XOR XOR XOR XOR XOR" (repeated) | 17 |
| `8` | — | Spoken expansion of 8,888,888,888 (extreme repetition) | 7 |
| `9` | — | "storage" | 31 |
| `10` | — | "ten ten ten ten...ten eleven ten ten ten ten ten" | 13 |
| `11` | — | Cryptic lines, song lyrics | 24 |
| `13` | — | Several behaviors, including corrupted event subroutine message | 24 |
| `19` | — | "This event subroutine is not currently available. Do not try again later." | 20 |
| `20` | — | Repetitive noise, like radio mode or machine | 21 |
| `22` | ADDITIONAL WARNINGS | Slowly evolving message. 325 calls logged. See [22# Changes](#22-changes). | 325 |
| `23` | — | Noise | 30 |
| `25` | — | AS install confirmation | 11 |
| `26` | — | "License key UK5 41 36 N9 J6 LX4" | 11 |
| `27` | — | Test message entered using word processing console | 19 |
| `28` | — | Test forward confirmation | 6 |
| `29` | — | Version brag | 8 |
| `30` | — | Prompts for travel request form submission | 7 |
| `31` | — | "Please wait. The number you are calling from has been recorded. Thank you. You may now hang up." | 6 |
| `36` | — | "Current load: 0.0.1" | 18 |
| `37` | ABISM | ABISM modem signal | 13 |
| `38` | ABISM | ABISM modem signal | 15 |
| `111` | — | "Excuse me. Your time is up..." | 19 |
| `112` | — | Garbled speech and other behaviors | 19 |
| `134` | — | Alphabet and Numbers | 7 |
| `136` | — | Lexicon | 5 |
| `211` | — | Electronic tones which sound like they're from a toy | 16 |
| `222` | — | "one" and other peculiarities | 35 |
| `230` | — | "Understand. The- situation. The- environment. And the- cause. For or beauty forever forever beautiful." | 8 |
| `231` | — | "Beautiful." | 10 |
| `232` | — | Dialing J | 13 |
| `272` | — | Cleveland Direct / Worm Seed Ordering Hotline | 13 |
| `303` | — | "You have reached the Time-Warner switch in Aurora, Colorado. The switch CLLI is A U R S C O F W R S 0" | 11 |
| `364` | — | Dialed very frequently in 2012 | 726 |
| `555` | CONFERENCE | ADHOC CONFERENCE BRIDGE | 27 |
| `559` | OPS CONF | OPERATIONS CONFERENCE | 19 |
| `1320` | ABISM MAPS | ABISM MAPS SERVICE | 54 |
| `2222` | — | "Please. Do not dial this agent code. Use agent code 22 for additional warnings. You have been warned. Goodbye." | 58 |
| `2600` | — | Some tones (tribute to 2600 Hz — the classic phone phreak frequency) | 8 |
| `2896` | — | Early NATO phonetic alphabet message source | 467 |
| `5000–5999` | — | Range | 1050 |
| `6569` | — | "pending" | 18 |
| `6871` | OTP BLACK 1 | OTP Black status | 5 |
| `6872` | OTP BLACK 2 | OTP Black status | 9 |
| `6873` | OTP BLACK 3 | OTP Black status | 35 |
| `6874` | OTP BLACK 4 | OTP Black status | 12 |
| `6875` | OTP BLACK 5 | OTP Black status | 30 |
| `6876` | OTP BLACK 6 | OTP Black status | 34 |
| `6877` | OTP BLACK 7 | OTP Black status | 7 |
| `6878` | OTP BLACK 8 | OTP Black status | 6 |
| `6879` | OTP BLACK 9 | OTP Black status | 11 |
| `6880` | — | Bell code reference | 12 |
| `8888` | SHIP | Source of SHIP messages (Arctic/ocean GPS coordinates) | 226 |
| `9696` | — | "This code has been compromised" (2012) | 16 |
| `9999` | — | Iridium Satellite Global Network | 4 |
| `10396` | — | "How, know, how how how" | 9 |
| `14000–14999` | VECTORTONE | VECTORTONE system | 546 |
| `16000` | — | Fast tones | 28 |
| `16001` | — | Agent AI Bouerges profile: DOB 062184, height 157, weight 49, Asian, COB JP | 60 |
| `16002` | — | Agent | 39 |
| `16003` | — | Agent | 7 |
| `16041` | AGENT | Primary field agent AI Bouerges — instructions, coordinates, drop announcements | 544 |
| `16042` | AGENT | Agent | 180 |
| `16043` | AGENT | Agent | 173 |
| `16044` | AGENT | Agent | 32 |
| `16045` | AGENT | Agent | 32 |
| `16241` | — | Handshake / upload for 16041 | 33 |
| `16242` | — | Upload for 16042 | 12 |
| `16243` | — | Upload for 16043 | 15 |
| `17000–17999` | ABISM | ABISM data range | 412 |
| `17003` | ABISM TUNE | "ABISM FREQUENCY TONES. TURN THE POTS WITH SCREW DRIVER UNTIL LED LIGHTS UP" | 15 |
| `17004` | CURRENT EPOCH | Current epoch timestamp | 12 |
| `18000–18999` | OTP MESSAGES | Main plot messages — XOR-encrypted with one-time pad | 2897 |
| `18003` | — | FILE_NOT_FOUND | 8 |
| `33330` | AGENT SYSTEM STATUS | | 87 |
| `33331` | FIRMWARELOAD | | 8 |
| `33332` | CHANNEL | | 13 |
| `33333` | VERSION | | 17 |
| `33334` | — | REBOOT or REVERSE AGENT NUMBER, USE ACCESS CODE | 31 |
| `33335` | — | HALT or AGENT MAINT | 18 |
| `33336` | — | Handshake | 13 |
| `33340` | — | 250.075 MHz (mostly) | 16 |
| `33350` | SIGNAL STRENGTH | "Signal strength is -85 dbm" | 15 |
| `33360` | — | 250.75 and noise | 5 |
| `33365` | RECORDER | AGENT SYSTEM RECORDER | 7 |
| `34154` | ZEUS STATUS | SATELLITE STATUS | 18 |
| `44812` | — | "Enter your verification code now." | 34 |
| `50000–59999` | — | Range | 237 |
| `56001` | — | Stand by / Your activation is now in pending state / ready state | 154 |
| `68700–68799` | SSTV | SSTV image range | 24 |
| `0096001` | EMTANON | | 17 |
| `99280–99290` | — | Drop coordinate systems (original run) | 1301 |
| `99280` | — | | 22 |
| `99281` | — | | 9 |
| `99284` | — | | 33 |
| `99286` | — | | 495 |
| `99288` | — | | 366 |
| `99289` | — | | 4 |
| `99290` | — | | 360 |
| `99990` | — | "Activity confirmed. Please disconnect now." | 8 |
| `99991` | — | "Activity confirmed. Please disconnect now." | 4 |
| `99992` | — | "Response accepted." | 5 |
| `99998` | — | "Maintenance mode on." | 7 |
| `99999` | — | "Maintenance mode off." | 9 |
| `160410–160450` | — | Extended agent codes | 51 |
| `190000–199999` | — | Mostly "zero" or "one" responses | 632 |
| `190001–190003` | — | "zero" | ~145 each |
| `190004` | — | "one" | ~145 |
| `229443` | — | "This agent code has been compromised." | 6 |
| `668187` | — | "Enter Zeus sequence number" | 26 |
| `674826` | — | CHANNEL 3 / PRJMLPL/75x5 instructions | 53 |
| `899053` | — | Radio tones / system directory | 18 |
| `2222222` | — | Honeypot — mentions instructions to establish honeypot to reduce burden on MLPL | 14 |
| `4064436` | STAMP CODE | Monitor for timing signals | 101 |
| `6360322` | — | Material Order Desk Forward | 31 |
| `15048801` | — | From Bulgaria video | 3 |
| `26037183` | — | "unholy racket" | 39 |
| `50565732` | ROBBYBOX | Robby's secret internal voicemail — whistleblower Robert Bramble | 273 |
| `55229382` | — | Green Book friendly code | 9 |
| `68101446` | — | "Speak report after the tone." | 7 |
| `123456789` | — | Counting | 16 |
| `139028188` | ENABLER | SUBSYSTEM ENABLER CODE | 8 |
| `150120587` | HF | Long, revealing conversations at specific times | 244 |
| `482608885` | — | El Cerrito friendly code | 4 |
| `891038117–118` | SSTV | SSTV range | 4 |
| `4822010112` | — | Green Book instructions | 23 |
| `25225733315` | — | "...Please press reset on controller card..." | 12 |
| `48260888882` | — | Model Info friendly code | 2 |
| `48902716041` | — | From Bangkok video (1:42) | 6 |
| `56990721710` | — | From Bangkok video (4:24) | 4 |
| `78974412697` | — | From Bangkok video (3:16) | 4 |
| `8988169312000368443` | — | "To enable service, please enter the ICCID on your card after the prompt." | 3 |

---

## Code Ranges Summary

| Range | Function | Total Calls |
|-------|----------|-------------|
| `0–99` | Core system messages, diagnostics, ABISM | ~500 |
| `100–999` | Extended messages, conference bridges | ~200 |
| `1000–9999` | ABISM, OTP Black, SHIP, ZEUS, Iridium | ~550 |
| `14000–14999` | VECTORTONE | 546 |
| `16000–16999` | Agent numbers/voicemail | 1280+ |
| `17000–17999` | ABISM data | 412 |
| `18000–18999` | OTP Messages (main plot) | **2897** |
| `33330–33399` | System diagnostics | 240 |
| `50000–59999` | Extended range | 237 |
| `68700–68799` | SSTV images | 24 |
| `99280–99290` | Drop coordinates | 1301 |
| `99990–99999` | Maintenance | ~33 |
| `190000–199999` | Binary-ish responses | 632 |

---

## 22# Changes

Agent code `22` ("Additional Warnings") is unique in that its message has changed gradually over time — hundreds of times, documented in a visualization at http://303.sashahart.net/messages/22/changes.

This is slow-burn narrative design: a single code whose message imperceptibly shifts, like a living document. The changes are small — a word here, a sentence there — but over time the message has transformed substantially. The visualization shows when each change occurred and what was altered.

The `2222` and `22222` codes are escalating variants: `2222` warns you not to dial `2222` and to use `22` instead. The pattern suggests a deliberate escalation trap.

---

## Revival-Era Agent Codes (AS32)

The revival uses a significantly expanded code space. Key additions not in the original run:

| Code | Function |
|------|----------|
| `301/302/303` | Slate messages (previously only `303` was a system code) |
| `55559` | "Melter" — prompts for input; possibly MXP20 machine code upload |
| `6824418` | Message Desk (now AS32, was 2022042303) |
| `238018300–399` | SSTV range |
| `18000–19999` | XORFS messages (XOR-encrypted with otp-blue-1.bin) |
| `22000–22999` | XORFS messages (continued) |

Full revival code documentation is maintained at https://otp22.org.
