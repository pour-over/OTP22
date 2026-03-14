# Decoding Techniques

*How to decode OTP22's various encrypted and encoded systems.*

---

## XOR / One-Time Pad Decryption

Used for: XORFS messages (AS32 18000–19999, 22000–22999) and Slate messages (301/302/303)

### XORFS Messages
1. Call AS32 (`+1-606-722-0004`), enter an 18xxx or 22xxx code
2. Transcribe the NATO phonetic alphabet sequence:
   - Alpha=A, Bravo=B, Charlie=C, Delta=D, Echo=E, Foxtrot=F, digits 0–9 as spoken
3. Convert hex string to byte array
4. Note the offset value spoken at the end
5. Open `otp-blue-1.bin` at the stated byte offset
6. XOR ciphertext bytes against key bytes: `plaintext[i] = cipher[i] XOR key[offset+i]`
7. Convert plaintext bytes to ASCII

**Tool:** https://otp22.org/tools/ (OTP XOR Decoder)

### Slate Messages
1. Call AS32, enter 301, 302, or 303
2. Note: sequence number, date (YYMMDD), decimal values, which story (301/302/303)
3. Open your *Slate Deposits in the Intermountain West* book to the appropriate section
4. Find the row number matching the sequence number
5. XOR each spoken decimal against the corresponding book row value
6. Convert to ASCII

**Tool:** https://otp22.org/tools/ (Slate Deposits Decoder)

---

## Steganography (Steghide)

Used for: El Paso drop portrait JPEGs and Amber Terminal files

```bash
steghide extract -sf Maria_1.jpg
```

When prompted for a passphrase, try:
- Empty passphrase (just press Enter)
- Agent codes, friendly codes, or other known strings

The Maria_1.jpg from El Paso yielded friendly code: `55 29 54 88 84 46 06 26`

**Tool:** `steghide` (command-line, available on Linux/Mac)

---

## SSTV Decoding

Used for: Terminal screenshots and drop location images from AS32

1. Call AS32, enter an SSTV code (3#, 10#, 11#, or 238018300–399 range)
2. Play the audio through your computer's microphone input
3. Run SSTV decoding software simultaneously (MMSSTV, RX-SSTV, or fldigi)
4. The software will automatically detect the SSTV mode and decode the image

---

## NATO Phonetic Transcription

XORFS messages are read back in NATO phonetic alphabet. Quick reference:

| Letter | NATO | Letter | NATO |
|--------|------|--------|------|
| A | Alpha | N | November |
| B | Bravo | O | Oscar |
| C | Charlie | P | Papa |
| D | Delta | Q | Quebec |
| E | Echo | R | Romeo |
| F | Foxtrot | S | Sierra |
| G | Golf | T | Tango |
| H | Hotel | U | Uniform |
| I | India | V | Victor |
| J | Juliet | W | Whiskey |
| K | Kilo | X | X-ray |
| L | Lima | Y | Yankee |
| M | Mike | Z | Zulu |

Digits 0–9 are spoken as words: zero, one, two, three, four, five, six, seven, eight, niner.

---

## ABISM Decoding

1. Record the audio from the relevant AS32 code
2. Upload the recording to the ABISM decoder at https://otp22.org/tools/
3. The decoder will attempt to extract the data stream

Note: ABISM is not fully decoded. The tool is community-built through reverse engineering of audio samples. Results may be incomplete.

**Also:** See [systems/protocols/abism/index.md](../systems/protocols/abism/index.md)

---

## TAMI, M6, M7 Decoding

Similar process to ABISM:
1. Record audio from agent system
2. Upload to appropriate decoder at https://otp22.org/tools/

---

## ITA2 / Baudot Decoding

Used in original run (2012-10-18 message):

ITA2 is 5-bit Baudot encoding used by TTY/teletype machines.

**Tool:** http://bagud.dk/arg/horns/ita2/

---

## PSK31 / BPSK31 Decoding

PSK31 is a narrow-bandwidth HF digital mode.

**Tool:** fldigi or similar digital mode decoder
- Set mode to PSK31
- Record/play audio through decoder

Used in OTP22 to hide drop coordinates in what appeared to be music (Blyind Tucson drop).

---

## Bell 103 Modem (AS32 Code 2)

Bell 103 = 300-baud FSK modem standard.

1. Call AS32, enter code `2`
2. Connect audio output to a Bell 103 modem or software decoder
3. Receive telemetry data at 300 baud

---

## Friendly Code Verification

To verify a friendly code found in a drop or decoded message:
1. Call AS32 (`+1-606-722-0004`)
2. Enter code `16000`
3. Enter the friendly code sequence via DTMF
4. System will confirm or deny

Known verified friendly codes:
- `55 29 54 88 84 46 06 26` (from Maria_1.jpg, El Paso drop)
- `55229382` (Green Book friendly code — agent code format)
- `482608885` (El Cerrito friendly code)
- `48260888882` (Model Info friendly code)

---

## MIDI Binary Decoding (Irving Drop)

The Irving TX drop MIDI file has notes arranged as binary data:
1. Open MIDI in a piano roll editor
2. Map notes to bits (e.g., note on = 1, note off = 0, or specific pitch ranges)
3. Group bits into bytes
4. Identify file signature or text encoding

This puzzle is unsolved. The mapping scheme is not yet confirmed.
