# ABISM Messages — Protocol Archive

**Source:** http://303.sashahart.net/messages/abism
**Total messages:** 71 entries
**Agent codes:** 17000–17999 (412 calls), also ** (14 calls), 37 (13 calls), 38 (15 calls), 1320 (54 calls)
**Status:** Partially decoded — custom modem protocol, technically challenging

---

## About ABISM

ABISM is a proprietary audio modem protocol developed for (or by) the MLPL organization. It appears to be a custom encoding of ASCII/SIXBIT data over audio tones, likely designed for transmission over telephone lines and potentially radio (HF).

Key facts:
- First documented: 2012-10-05 on 7097000122 code 0 ("ABISM tones" + busy signal)
- Multiple versions exist: ABISM v1, v2, Chop-4 rev, DEC SIXBIT + mark parity
- Community built a decoder tool at http://otp22.org/tools/
- **ABISM is referenced as a way to upload new agent codes** (per Robby's disclosure)
- Appears to function as an interactive terminal interface (prompt: `REQ>`)
- ABISM MAPS SERVICE at agent code 1320 (54 calls — possibly a navigation/coordinate system)

---

## Technical Analysis

### Observed Variants

| Variant | First Seen | Notes |
|---------|-----------|-------|
| ABISM v1 | 2012-10-05 | Initial tones |
| ABISM (DEC SIXBIT + mark parity) | 2012-12-15 | Interactive terminal, `REQ>` prompt |
| ABISM v2? | 2012-12-15 | May be same as DEC SIXBIT variant |
| ABISM Chop-4 rev | 2013-01-28 | Different encoding, gives numeric output |
| ABISM v1 (17010) | 2013-02-26 | Another variant |

### Decoded Outputs

The most significant decode came from code **17011** (2013-02-23):

```
VFHFFD\X@TZTH
]]^@XH
]]^@QUITTHXOTHING FOUND FOR [QUIT]TH
]]^@HELPTH
]]^@GO HELP INDEX PRINT READ WRITE TH
]]^@EXIT TH
XOTHING FOUND FOR [EXIT]TH
]]^@QUITTH
XOTHING FOUND FOR [QUIT]TH
```

Decoded (DEC SIXBIT -1):
```
==>
==> (prompt)
NOTHING FOUND FOR 'EXIT'
NOTHING FOUND FOR 'QUIT'
==> HELP
==> GO HELP INDEX PRINT READ WRITE
==> EXIT
NOTHING FOUND FOR 'EXIT'
NOTHING FOUND FOR 'QUIT'
```

**This confirms ABISM is an interactive command-line terminal system** with commands: GO, HELP, INDEX, PRINT, READ, WRITE.

### Chop-4 Rev Outputs

Code 17002 (2013-01-28): `0:44888080<0001359413806`
Code 17002 (2013-02-13): `0:448880<0001360716703`

The format appears to be: `[flag]:[data_block]<[timestamp_or_checksum]`

---

## Message Archive

### 2012-10-05 — First ABISM
**7097000122 code 0**
[wav](http://dialer.otp22.com/2012-10.dir/2012-10-05%2022-12%20UTC%20-%20709-700-0122%20-%200.wav)
```
<ABISM tones>
<ringing>
Your call could not be completed as dialed. Please check your number and dial again. 2 B M.
Your call cannot be completed as dialed. Please check your number and dial again. 2 B M.
<ABISM tones>
```

### 2012-12-15 — ABISM Terminal (17001)
**2029993335 17001** — DEC SIXBIT + mark parity
[wav](http://dialer.otp22.com/2012-12-15%2021-04%20UTC%20-%20202-999-3335%20-%2017001.wav)
```
==========
ABISM
==========
REQ>  (pause)
REQ>  (pause)
REQ>
```

### 2012-12-27
**2029993335 16002** — short ABISM tones
[wav](http://dialer.otp22.com/2012-12.dir/2012-12-27%2009-28%20UTC%20-%20202-999-3335%20-%2016002.wav)

### 2013-01-28 — ABISM Cross-References
**16042:** `468:18027` (→ references OTP message 18027)
**16043:** `468:18101` (→ references OTP message 18101)
[wav 16042](http://dialer.otp22.com/2013-01-28%2016-45%20UTC%20-%20202-999-3335%20-%2016042%23.wav)
[wav 16043](http://dialer.otp22.com/2013-01-28%2016-45%20UTC%20-%20202-999-3335%20-%2016043%23.wav)

### 2013-01-28 — Chop-4 Rev
**17002:** `0:44888080<0001359413806`
[wav](http://otp22.com/2013-01-28%2022-56%20UTC%20-%20202-999-3335%20-%2017002%23.wav)

### 2013-02-13 — Chop-4 Rev Update
**17002:** `0:448880<0001360716703`
[wav](http://dialer.otp22.com/2013-02-13%2000-51%20UTC%20-%20202-999-3335%20-%2017002%23.wav)

### 2013-02-18 — More Cross-References
**16042:** `468:18053`
**16043:** `468:0004`

### 2013-02-23 — ABISM Terminal Help
**17011** — DEC SIXBIT decode (see above — interactive help menu)
[wav](http://dialer.otp22.com/2013-02-23%2000-35%20UTC%20-%20202-999-3335%20-%2017011%23.wav)

### 2013-02-25 — Z-Code
**16042:** `Z809331`
[wav](http://dialer.otp22.com/2013-02-25%2005-53%20UTC%20-%20202-999-3335%20-%2016042.wav)

### 2013-02-26 — ABISM v1 (17010)
[wav](http://dialer.otp22.com/2013-02-26%2017-16%20UTC%20-%20202-999-3335%20-%2017010.wav)

---

## Key ABISM Agent Codes

| Code | Description | Calls |
|------|-------------|-------|
| ** | ABISM | 14 |
| 37 | ABISM | 13 |
| 38 | ABISM | 15 |
| 1320 | ABISM MAPS SERVICE | 54 |
| 17000–17999 | ABISM range | 412 |
| 17001 | DEC SIXBIT interactive terminal | — |
| 17002 | Chop-4 rev data stream | — |
| 17003 | **ABISM TUNE**: "TURN THE POTS WITH SCREW DRIVER UNTIL LED LIGHTS UP" | 15 |
| 17004 | CURRENT EPOCH | 12 |
| 17010 | ABISM v1 | — |
| 17011 | Interactive terminal (help menu decoded) | — |

**17003 message:** "ABISM FREQUENCY TONES — TURN THE POTS WITH SCREW DRIVER UNTIL LED LIGHTS UP"
→ Implies physical hardware (a device with adjustable potentiometers and an LED indicator) used with ABISM.

---

## Community Decoder

The OTP22 community built an ABISM decoder tool available at:
**http://otp22.org/tools/**

This is one of the major unsolved puzzles from the original run that carried into the revival era.

---

## Robby's Disclosure (from Robbybox)

> "There are several ways to upload new agent codes, one of which can be done with a modem. There is X.25... There is a TDD... Then there is ABISM, of course."

This confirms ABISM can be used to upload/modify agent code content, making it a read-write interface to the phone system, not just a read-only message delivery mechanism.

---

*All audio: http://dialer.otp22.com/*
