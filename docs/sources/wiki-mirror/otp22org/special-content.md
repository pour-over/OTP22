# Special Content — otp22.org Wiki Mirror

This page covers unique narrative content not fitting other categories: Felicity's diary, Felicity's voicemail, the Message Desk, postal mail, and steganography.

---

## Felicity's Diary

**Source:** https://otp22.org/doku.php?id=felicity_s_diary

A personal diary kept by Felicity Love documenting her journey from innocent Emtanon intern to fugitive. **58 sections** indexed. The diary is one of the richest narrative documents in the revival era.

### Chapter Structure

**Pre-Gough entries:**
- First entry, New job, David, Friends
- [PRIVATE] — locked entry
- New job (2nd), Paperwork, Island, Plane ticket, Boring

**Gough Island:**
- Week 1, Stopped, Weird boat, Week 2, Land!, First impressions, Weird, Island life, Hike
- [PRIVATE] — locked; contained the **Federal Way drop coordinates** (unlocked by community)

**On the run:**
- Stupid blog, Front, Weather, Gorno, Door, Weather, Jeff, Picnic, Phone numbers, Shady, Books, Russians
- Jeff (2nd), Sacred, Missing, Drop agents, A folder, My stuff, Concerning, Green screen, Another note
- Scary meeting, !Last message!
- Brazil, Sao Luis, Following me, Circuits, Paranoid, :(
- [PRIVATE] — locked entry

### Key Entry: [PRIVATE] — The Federal Way Coordinates

One of the locked diary entries (marked [PRIVATE]) contained the location of the **Federal Way drop**. Jeff wrote the coordinates and an SSTV agent code on Felicity's hand during a hiking date, telling her to post them on Instagram. The community unlocked the entry through solving associated puzzles.

---

## Felicity's Voicemail

**Source:** https://otp22.org/doku.php?id=felicity_s_voicemail

**31 sections** indexed. The voicemail functions as a passive dead drop signal system — SSTV images of drop sites appeared here, allowing the community to identify locations.

### Entry Archive

**July 2023 (14 entries):**
- Entries 1–14 document Felicity's flight from Gough Island through her time on the US East Coast

**September 2023:**
- Entries 1–8: SSTV images — see [Slide Cemetery drop](dead-drops.md#slide-cemetery-drop)
- Entry 9, Entry 10

**October 2023:**
- SSTV images for Riverside drop (deleted by Desiree Martin except two images)
- SSTV images for Tuktoyaktuk drop

**November 2023 onward:**
- Additional entries as Felicity goes quiet after the manhunt is canceled

### Significance

The voicemail was the primary signal for Jeff-placed drops during fall 2023. Marine Org operative **Desiree Martin** deleted detailed location photos from multiple entries to hinder drop retrieval — only the Slide Cemetery and Riverside partial images survived her interventions.

---

## Message Desk

**Source:** https://otp22.org/doku.php?id=message_desk
**Access:** Dial AS32 (+1-606-722-0004), enter agent code `6824418`

The Message Desk is operated by a **real human operator** who responds to numeric prompts. It is the most direct player-to-gamemaster communication channel in the revival.

**Discovery:** January 7, 2024. The code was hidden in the Ruston copy of *Slate Deposits in the Intermountain West*.

**Hours:** Operating schedule currently unknown. "Pending" entries appear at a later time according to operators.

**Original-run connection:** The Message Desk was active intermittently 2012–2014. Historical interactions are partially archived at web.archive.org.

---

## Postal Mail

**Source:** https://otp22.org/doku.php?id=mail

Some items are only obtainable by sending physical postal mail to:

```
615 US-9 S #172
CMCH, NJ 08210
USA
```

(CMCH = Cape May Court House, NJ — location of Debbie Wright, Field Agent Coordinator)

### Available Mail Options

| Addressee | What you get |
|-----------|-------------|
| **Access Request** | Request access to Emtanon's systems using form AC-P-REQ-01. Requires credentials from the Drop Agent Catalog first. |
| **CD** | Request a [Cleveland Direct](agent-systems.md#cleveland-direct) calling card (limited minutes). |
| **Drop Agent Catalog** | Request credentials to the [Emtanon portal](https://emtanon.com/portal/). |
| **Literature Request** | Request one of the revival [books](books.md) (physical copy). |

---

## Steganography

**Source:** https://otp22.org/doku.php?id=steganography

Several image files from the **El Paso drop** contain hidden data encoded with `steghide`.

### Confirmed Steganographic Files

| File | Status |
|------|--------|
| Maria_1.jpg | Confirmed — example used on wiki page |
| Other El Paso JPGs | May also contain data |

### How to Decode

1. Install `steghide`:
   - **Windows/Linux:** https://steghide.sourceforge.net/
   - **Mac:** `brew install steghide`

2. Run:
   ```bash
   steghide extract -sf filename.jpg
   ```

3. Enter passphrase when prompted

**File source:** https://otp22.org/files/elpaso/

### Unsolved

The steganographic content of most El Paso images has not been fully decoded. The `insurance.bin` file (also from El Paso) is a separate unresolved mystery — a large binary hinted by XORFS 18438 to contain dirt on Debra Fisher.
