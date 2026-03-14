# Data Files Index — Mirror

**Source:** http://303.sashahart.net/files

> All digital files recovered from physical drops or associated with the OTP22 game.

---

## Files Table

| File / Description | Filename | Drop Origin | Notes |
|-------------------|----------|------------|-------|
| Ubuntu 12.04 CD image | ubuntu-12.04-desktop-i386.iso | — | Standard OS |
| OTP text files | otp.txt, p1.txt–p4.txt | Lake Oswego | One-time pad material |
| Lake Oswego CD image | cdimg.iso | Lake Oswego | — |
| bcwipe3.exe | bcwipe3.exe | Blue Hill | Secure file deletion tool |
| TrueCrypt Setup 5.1a.exe | TrueCrypt Setup 5.1a.exe | Blue Hill | Encryption software — old version |
| data.bin | data.bin | Blue Hill | — |
| Blue Hill CD image | CD Image.iso | Blue Hill | Contains: bcwipe3.exe, TrueCrypt, data.bin |
| Bangkok DVD image | COLLECTING_VINTAGE_CAPACITORS.iso | Bangkok | Named after an ExcitingBooks title |
| El Paso CD image | — | El Paso | — |
| El Paso Hole | weirdblock.bin | El Paso | Unexplained binary data |
| Smugtrio floppy image | — | Smugtrio #1 | 5.25" DOS 3.1 BACK-UP floppy |
| Smugtrio CD image | — | Smugtrio #1 | — |
| Iridium SIM card image | — | Henderson | Key to satellite comms |
| DRAM card image | — | Rainier #1 | — |
| Bulgaria CD image | — | Dimitrovgrad | Contains: IFFOUND.TXT, SHOPPING.TXT, data.bin |
| Bulgaria video | — | Dimitrovgrad | Contains DTMF tones at 2:01, 2:26 |
| NYC CD image | — | NYC | Contains: data1-4.bin, file.txt, IFFOUND.TXT, ORDER.TXT |
| NYC MicroSD image | — | NYC | Contains: data1-4.bin, file.txt, p1.txt |
| Carlisle CD image | — | Carlisle | Contains: VERIFY.TXT, IFFOUND.TXT, AGENTCODES.TXT, p1-2.txt, MODEL-NUMBERS.TXT, PHONENUMBERS.TXT |
| El Cerrito Data CD image | — | El Cerrito | — |
| El Cerrito Hole | elcerrito.bin | El Cerrito | Unexplained binary block |
| El Cerrito Audio CD image | california-drop.dmg | El Cerrito | Contains: 1AudioTrack.aiff, 2AudioTrack.aiff, associated PDFs/TXTs |
| OTP7 CD image | — | Kauai | Lord_Pall |
| OTP8 CD image + hole | black OTP 8.bin | Kauai | — |
| OTP9 CD image + hole | black OTP 9.bin | Kauai | — |
| Newport Beach CD + hole | otp_4_newport.bin | Newport Beach | — |
| North Dakota CD + hole | north_dakota.iso, otp_2_north_dakota.bin | North Dakota | — |
| Kauai Worm Book PDF | worms-ocr.pdf | Kauai | OCR of Designing Compelling Worm Sanctuaries |
| Global Response Codes PDF | ocr-globalresponsecodes.pdf | Nadando | OCR of the Dr. J. Marvin Blackweather book |
| Letters | letter.pdf, highres-letter.PDF | Various | — |
| Key data files | 0.txt–9.txt, A.txt–D.txt | Various | — |
| DiVA VideoShop | DiVA VideoShop 1.0se.zip | — | Software |
| Chicago CD image | — | Chicago | "Bellwood" label |

---

## Notable Binaries

### weirdblock.bin (El Paso)
An unexplained binary block found in the El Paso drop. The "hole" files (weirdblock.bin, elcerrito.bin, black OTP files) are binary data blocks that community members attempted to decode as additional OTP key material or encoded messages.

### COLLECTING_VINTAGE_CAPACITORS.iso (Bangkok)
DVD image named after an ExcitingBooks title. The naming convention — using absurdist fake book titles as filenames — is a consistent signature of the OTP22 puppetmaster team.

### data.bin (Blue Hill, Bulgaria)
Binary blobs appearing in multiple drops. Some were decoded as XOR-encrypted messages using known OTP material.

### PHONENUMBERS.TXT (Carlisle)
Contains additional phone numbers. Confirmed numbers from this file include many of the 0004-suffix Level 3 DID numbers.

---

## Standard Drop CD Contents

Most CDs followed a predictable structure:
```
/IFFOUND.TXT    - Contact information / game instructions
/data.bin       - Encoded payload (XOR or other)
/p1.txt         - OTP key material (sometimes p1-p4)
```

Bulgaria and NYC added:
```
/SHOPPING.TXT   - Lists of items (narrative content)
/ORDER.TXT      - In-game order forms
/AGENTCODES.TXT - Agent code lists (Carlisle)
/PHONENUMBERS.TXT - Phone number lists (Carlisle)
/MODEL-NUMBERS.TXT - Hardware model numbers (Carlisle)
```
