# 18xxx Messages — OTP Decoded Narrative Archive

**Source:** http://303.sashahart.net/messages/18xxx
**Agent code range:** 18000–18999
**Total calls logged:** 2,897
**Sections indexed:** 281
**Encoding:** XOR cipher against physical OTP CD material

---

## About 18xxx Messages

The 18xxx agent codes are the primary narrative delivery mechanism of OTP22. Messages are:

1. **Recorded** as sequences of numbers spoken by TTS (Text-To-Speech)
2. **Transcribed** by community members as lists of integers (0-255)
3. **XOR-decoded** against the One-Time Pad key material from physical CDs
4. **Formatted** as military-style signals intelligence messages

**Header format:**
```
Z [DDHHMMZ] [MON] [YY]
SECRET//PRJMLPL//75X5
MSGID/[sender]//
SUBJ/[subject]//
/FORMAT/OBJ/[number]/ASCII//
/OBJ/[number]/
[message body]
//
```

**Key:** `PRJMLPL` = Project MLPL (the organization name). `75X5` = classification code.

---

## Message Archive (Decoded)

### 18001 — First Message (2012-12-13)

```
Z 130001Z DEC 12
SECRET//PRJMLPL//75X5
MSGID/A16041_131212_1//
SUBJ/STATUS//
/OBJ/00001/
GOOD SEASON, LIMITED LOSSES BUT COMPONENTS FAILED TO REACH SVALBARD.
MAY BE EXPERIENCING COMPONENT LOSS AT DROP SITES.
SUSPECT ROGUE AGENT OR COUNTER OPERATION.
MISSION CANNOT CONTINUE UNLESS RECOVERED.
TWO AGENTS ASSIGNED TO DETERMINE THREAT.
MAY NEED ASSISTANCE IN RECOVERY.
OTP AUTH CODE 30004A ASSIGNED UNTIL FURTHER NOTICE.
SIGNAL EMERG IF OTP COMPROMISED OR ADDTNL SPACE REQUIRED.
//
```
*First message establishes the core premise: components went missing, possible rogue agent, mission compromised.*

Audio: [303-309-0004](http://dialer.otp22.com/2012-12-13%2006-36%20UTC%20-%20202-999-3335%20-%2018001.wav) | [wiki](http://otp22.referata.com/)

---

### 18029 — Rainier Drop Orders

Coordinates referencing the Oregon Rainier drop location and collection instructions.

---

### 18034 — Green Book Status

```
STATUS REPORT ON GREEN BOOK IN DROP 642.
```

---

### 18040 — Chartreuse (2013-02-09)

```
Z 08212259Z FEB 13
SECRET//PRJMLPL//75X5
MSGID/COLOR//
SUBJ/CHARTREUSE//
/OBJ/00001/
PROVIDE CHARTREUSE TO MESSAGE DESK.
VERBAL INSTRUCTIONS WILL FOLLOW.
//
```

---

### 18053–18056 — Bangkok Drop Coordinates (2013-02)

18054 contained the Malaysia drop coordinates; 18056 the Bangkok drop coordinates.

---

### 18073 — Santa Clara Drop

Santa Clara, CA drop coordinates and retrieval instructions.

---

### 18084 — Ft. Lauderdale Drop (2013-04-29)

Referenced in Cleveland Direct calling card system. Airport payphone SSTV image.
Related number: 8888542402 (Material Order Desk / Network Services Complex)

---

### 18087, 18093 — NYC Drops

```
[NYC drop coordinates and instructions]
```
18087 via 2029993335; 18093 via 3033090004.

---

### 18098 — Carlisle Drop

Carlisle, PA drop. CD contained: VERIFY.TXT, IFFOUND.TXT, AGENTCODES.TXT, PHONENUMBERS.TXT, MODEL-NUMBERS.TXT.

---

### 18109 — El Cerrito Drop (2013-06)

El Cerrito, CA. Data CD + Audio CD.

---

### 18114 — D/OTP Reference

Referenced by Robby as containing a number (272649905).

---

### 18119 — Black OTP Reference

References number 2723649905.

---

### 18134, 18141 — Bulgaria Drops

18134 → Dimitrovgrad drop.
18141 → Sofia drop.

---

### Season 2013 Deliverables Messages

**From codes 48902716041 and 56990721710 (decoded via Bangkok video):**

```
//FREEFORM/
SEASON 2013 DELIVERABLES
========================
PER 4(B)K OF WO 9482.9M
DISPATCH TRANSP TO JOIN MELTER FLEET WINTER POSITION
AT 80.3886 5.6538 FOR OPERATION DESCRIBED IN 4(B)G-L.
AREA HAS BEEN CLEARED.
AFTER OPERATION, TRANSP MUST TRAVEL TO FACILITY INDICATED IN 4(B)L.
*CONT*
//
```

```
//FREEFORM/
SEASON 2013 DELIVERABLES CONT
==============================
TRANSP MISSION: DELIVER PAYLOAD.
PER 9482.9M 4(B)M,
PAYLOAD WILL BE COMPLETED BEFORE DEPARTURE.
SEE WORM BOOK FOR FURTHER DETAILS.
//
```

**SVALBARD coordinates decoded:** 80.3886°N, 5.6538°E — this is in the Barents Sea north of Svalbard.

---

### Green Book / ZEUS Uplink (from 78974412697)

```
//FREEFORM/
UPLINK FACILITY 80.0350 16.2910 ONLINE.
MESSAGE TRANSPORT OPERATIONAL.
ZEUS FLYOVER RESOURCES IN GREEN BOOK.
PLEASE OBTAIN YOUR GREEN BOOK AT SPECIFIED LOCATIONS.
DISTRIBUTE ACCORDINGLY. PROTECT CONTENTS.
//
```

Coordinates 80.0350°N, 16.2910°E = Svalbard archipelago.

---

### Operation Messages — 2013 Season

**IRISLATCH operation (August 2013):**
- Melter Fleet (MELTR1, MELTR2, MELTR4) in position
- Fleet standby orders

**LONGVAULT operation (late 2013):**
- D heading to shore location
- System reactivation after Emtanon software bugs
- J switches to main channel

**674826 Channel 3 message (PRJMLPL):**
```
CHANNEL 3
PRJMLPL/75X5
YOUR ACTIVATION REQUEST HAS BEEN RECEIVED.
PREPARE YOUR EQUIPMENT FOR OPERATION AND CONTROL OF METLER FLEET
FOR THE NEW 2013 SEASON.
MONITOR THIS OFFICIAL CHANNEL FOR FURTHER INSTRUCTIONS.
```

---

### 18349 — J Requests Red Terminal

```
THE GREEN TERMINAL IS STUPID.
I WANT A RED ONE. -J
```
*(Source for why the Red Terminal was installed at Emtanon HQ)*

---

### 18398 — J's Drop Status Query (2015-03-02)

```
Z 02023234Z MAR 14
SECRET//PRJMLPL//75X5
MSGID/DROP AGENT//
SUBJ/DROP AGENT//
/OBJ/00001/
I NEED A STATUS ON THIS DROP. -J
//
```

---

## Message Format Reference

### Classification Headers
- `SECRET//PRJMLPL//75X5` — Standard classification header
- `Z [DDHHMMZ] [MON] [YY]` — Military date-time group
- `MSGID/[sender]//` — Message identifier with sender
- `SUBJ/[subject]//` — Subject line

### Sender Codes Used
- `A16041_XXXXXX_N` — From Agent 16041 (AI Bouerges)
- `COLOR` — Color/identifier system
- `DROP AGENT` — Drop agent communications
- `J` — Direct from J (often terse/demanding)

### Freeform Messages
Some messages use `//FREEFORM/` format with different encoding — typically longer operational orders.

---

## OTP Key Material

Messages are XOR-decoded using key material from physical CDs found in drops:

| Key | Source |
|-----|--------|
| OTP Auth Code 30004A | Assigned in message 18001 |
| OTP7 | Kauai drop CD |
| OTP8 | Kauai drop CD |
| OTP9 | Kauai drop CD |
| OTP Black (otp-blue-1.bin, 1GB) | El Paso drop — master key for XORFS in revival |

---

## Audio Reference

All 18xxx recordings: `http://dialer.otp22.com/YYYY-MM.dir/`
Format: `YYYY-MM-DD HH-MM UTC - [number] - 18XXX.wav`

Also: [Black OTP messages piratepad](http://piratepad.net/ep/pad/view/ro.d8eCRnXQI9K/latest)
