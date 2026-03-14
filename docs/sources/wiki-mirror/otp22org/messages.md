# Messages — otp22.org Wiki Mirror

**Source:** https://otp22.org/doku.php?id=messages

The story is advanced primarily through written messages attributed to characters. Four active message systems exist in the revival era, all accessed through AS32 (+1-606-722-0004).

---

## XORFS

**Source:** https://otp22.org/doku.php?id=xorfs
**Audio:** [as32-xorfs.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:as32-xorfs.flac) — Typical XORFS message

XORFS is the primary narrative message system — email-like exchanges between characters. Messages are found on AS32 sequentially, in ranges of agent codes.

### Format

XORFS messages are transmitted as:
1. `"Blue OTP 1 file start"`
2. Ciphertext: hexadecimal numbers spelled using the **NATO phonetic alphabet** (e.g., Alpha=A, Bravo=B, Charlie=C...)
3. `"Offset"` followed by the byte position of the key

**Decryption:**
- XOR cipher using `otp-blue-1.bin` (1 GB file from the El Paso drop)
- Key = fragment of that file starting at the given offset, equal in length to the ciphertext
- OTP XOR decoder tool: https://otp22.org/tools/otpxor.php
- OTP key file: https://otp22.org/files/elpaso/trash_files/otp-blue-1.bin

### Archived Message Ranges

Each range contains ~50 messages. Currently archived:

| Range | Wiki page |
|-------|-----------|
| 18000–18049 | https://otp22.org/doku.php?id=xorfs:18000-18049 |
| 18050–18099 | https://otp22.org/doku.php?id=xorfs:18050-18099 |
| 18100–18149 | ... |
| 18150–18199 | ... |
| 18200–18249 | ... |
| 18250–18299 | ... |
| 18300–18349 | ... |
| 18350–18399 | ... |
| 18400–18449 | ... |
| 18450–18499 | ... |
| 18500–18549 | ... |
| 18550–18599 | ... |
| 18600–18649 | ... |
| 18650–18699 | ... |
| 18700–18749 | ... |
| 18750–18799 | ... |
| 18800–18849 | ... |
| 18850–18899 | ... |
| 18900–18949 | ... |
| 18950–18999 | ... |
| 19000–19049 | ... |
| (continues through 19999) | ... |
| 22000–22049 | https://otp22.org/doku.php?id=xorfs:22000-22049 |
| (continues through 22999+) | ... |

**Key XORFS messages:**
- **18438**: Hints that `insurance.bin` (from El Paso drop) contains dirt on Debra Fisher
- **18818**: Agent `AO` requests 2024 Slate Deposits book for Las Vegas drop
- **22045**: Band demands release of their non-propaganda songs
- **22475**: Robby hints "Follow Her Not" will hit streaming soon
- **22505**: Points to AS32 Wailua drop coordinates

---

## Iris

**Source:** https://otp22.org/doku.php?id=iris

Iris is an **instant messaging system** used within the universe. It may be accessed from every terminal and from dedicated mobile units. Conversations happen in **real time** on the terminals.

### Talk Groups

Peers are identified using numeric talk groups. Negative numbers are mobile units.

| Talk group | Peer |
|-----------|------|
| `0` | ITOPS |
| `1` | HQ |
| `100` | MO1 |
| `112` | AIR1 |
| `201` | MO5 (previously MO3) |
| `211` | AIR2 |
| `291` | MO2 |
| `284` | Material order desk |
| `411` | Directory assistance |
| `555` | MO5 |
| `609` | MO6, Bridge |
| `660` | Shadow Team |
| `808` | Honolulu Tape Retrieval System |
| `15034` | Debra Fisher |
| `16001` | Esprit Boursicot |
| `54099` | FACILITY, Comms room |

### Notable Iris Conversations

- **Amber terminal Iris**: Revealed Tuktoyaktuk drop location was Arctic
- **Amber terminal Iris**: Live discussion of Ruston drop placement (January 2024)
- **Green terminal Iris**: Discussed Pawnee Rock drop placement for "rookie agent"
- **Amber terminal Iris**: Wailua drop reveal (November 2025)

---

## Slate Messages

**Source:** https://otp22.org/doku.php?id=slate_messages
**Audio:**
- [as32-slate.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:as32-slate.flac) — Typical Slate message
- [as32-slate-null.flac](https://otp22.org/lib/exe/fetch.php?media=agent_systems:as32-slate-null.flac) — Empty message

Slate messages are **very short texts** found on AS32 at agent codes `301`, `302`, `303` throughout 2024. Used for bidirectional communication between HQ and field agents. Each message broadcast for **24 hours starting at 00:00 UTC**.

### Format

```
Sequence number: [text]
```

Decryption tool: https://otp22.org/tools/slatexor.html

### Monthly Archives

- 2024: January, February, March, April, May, June, July, August, September, October, November, December (all 12)

### Key Slate Messages

| Code | Message | Result |
|------|---------|--------|
| 301 | `LFL 96704` | Nashville drop (April 2024) — Little Free Library #96704 |
| 301 | `34.486052 -93.047361 IN BRUSH` | Hot Springs drop (April 2024) |
| 301 | `35.72485 -83.51612 BELOW ROCK` | Gatlinburg drop (April 2024) |
| 302 | `SSTV. 22.12525 113.55755 ROCK` | Macau drop (February 2024) |
| 302 | `OK ITS AT 32.8210 -97.0093 *_*` | Irving drop (December 2024) — Maria Peters |
| 303 | (various) | General agent communications |

---

## AS27

**Source:** https://otp22.org/doku.php?id=as27
**Phone:** +1-207-813-2200

Organizational announcements, broadcast for 24 hours at a time. See [Agent Systems — AS27](agent-systems.md#as27) for full format details.

**Monthly archives:** https://otp22.org/doku.php?id=start&idx=as27

Coverage: May 2023 – present (including December 2025, early 2026).

---

## Message Desk

**Source:** https://otp22.org/doku.php?id=message_desk
**Access:** AS32 agent code `6824418`
**Discovered:** January 7, 2024

The Message Desk is operated by a **real person** who responds to number prompts. The agent code was found in the Ruston copy of the Slate Deposits book.

The Message Desk was previously active intermittently in 2012–2014 (original run).

**Operating schedule:** Currently unknown. Entries showing "Pending" will show up later according to operators.

**Historical archive:** https://web.archive.org (archived original-run interactions)
