# SSTV Messages — Slow-Scan Television Archive

**Source:** http://303.sashahart.net/messages/sstv
**Total entries:** 21 documented, many more in the 68700–68799 range (24 calls)
**Encoding:** SSTV (Slow-Scan Television) — standard amateur radio image protocol
**Primary agent codes:** 68700–68799 (SSTV range), also 16001, 16041, 16042, 16043 uploads

---

## About SSTV in OTP22

SSTV (Slow-Scan Television) is a standard method of transmitting still images over audio. In OTP22 it was used to:
1. **Announce drop locations** — images of the physical location where items were hidden
2. **Show terminal screenshots** — Green, Amber, Red terminal states (in revival)
3. **Transmit agent profile data** — combined with ITA2/RTTY
4. **Confirm uploads** — agent codes 16241/16242/16243 send `UPLOAD` via SSTV

Common SSTV mode: **Scottie 2** format

---

## Message Archive

### 2012-09-14 — Drop Announcements (Lake Oswego area)
Three recordings via 3033090004 code 99286:
- [wav 1](http://vocaroo.com/i/s0zUVJ2sqC0h)
- [wav 2](http://vocaroo.com/i/s0YdULQSc068)
- [wav 3](http://vocaroo.com/i/s0h2v6tUR8xH)

### 2012-11-24 — Agent 16001 Profile (SSTV + ITA2)
**2029993335 16001**
[wav](http://dialer.otp22.com/2012-11-24%2020-04%20UTC%20-%20202-999-3335%20-%2016001.wav)

Decoded content (agent profile):
```
YRY/FIRSTNAME/AI/LASTNAME/BOUERGES/DOB/062184/HEIGHT/157/WEIGHT/49/
ETHNICITY/ASIAN/COB/JP/ASSIGNDATE/100311/PASSPORT/JP/
EMERGAGENT/4840013/EMERGCODE/48420
```
*AI Bouerges: Japanese female, born 06/21/84, 157cm, 49kg, Japan passport, assigned 10/03/11*

### 2012-11-24 — Upload Confirmation
**2029993335 16241**
[wav](http://dialer.otp22.com/2012-11-24%2020-07%20UTC%20-%20202-999-3335%20-%2016241.wav)
Content: `UPLOAD`

### 2012-11-25 — Fast Tones (RTTY/SSTV mix)
**2029993335 16001**
[wav](http://dialer.otp22.com/2012-11.dir/2012-11-25%2003-35%20UTC%20-%20202-999-3335%20-%2016001.wav)
`<very fast tones with ticking in background> <other radio mode for a while>`

### 2013-02-12 — Kauai Drop Location Images
Three SSTV recordings showing drop hiding spots:

**2029993335 68771** [wav](http://dialer.otp22.com/2013-02-12%2001-32%20UTC%20-%20202-999-3335%20-%2068771.wav)
*3 SSTV images: a river, some mossy rocks, and some underbrush*

**2029993335 68781** [wav](http://dialer.otp22.com/2013-02-12%2001-30%20UTC%20-%20202-999-3335%20-%2068781.wav)
*Several SSTV images, in particular a niche under a rock outcropping*

**2029993335 68791** [wav](http://dialer.otp22.com/2013-02-12%2001-23%20UTC%20-%20202-999-3335%20-%2068791.wav)
*4 SSTV images of grass and a wooded area*

### 2013-02-19 — Malaysia/Bangkok Preview
**3033090004 891038117** [wav](http://dialer.otp22.com/2013-02-19%2006-58%20UTC%20-%20303-309-0004%20-%20891038117.wav)
*SSTV image of a red box thing*

**2029993335 891038118** [wav](http://dialer.otp22.com/2013-02-24%2006-48%20UTC%20-%20202-999-3335%20-%20891038118.wav)
*SSTV of a phone booth with Thai printed on it* — Bangkok drop preview

### 2013-03-14 — Upload Confirmations
**16242:** `UPLOAD` [wav](http://dialer.otp22.com/2013-03-14%2019-47%20UTC%20-%20202-999-3335%20-%2016242%23.wav)
**16243:** `UPLOAD` [wav](http://dialer.otp22.com/2013-03-14%2019-43%20UTC%20-%20202-999-3335%20-%2016243.wav)

### 2013-04-29 — Ft. Lauderdale Drop Preview
**2029993335 16041** [wav](http://dialer.otp22.com/2013-04-29%2022-33%20UTC%20-%20202-999-3335%20-%2016041.wav)
*Song, followed by 18084 reference, followed by SSTV image of airport payphones*

### 2013-05-08 — NYC Drop (Scottie 2)
**2029993335 16043** [wav](http://dialer.otp22.com/2013-05-08%2020-17%20UTC%20-%20202-999-3335%20-%2016043%23.wav)
*18087 reference followed by SSTV in Scottie 2 format*
Decoded SSTV image: http://i.imgur.com/Nyr6QYt. *(NYC drop location)*

---

## SSTV in the Revival Era

In the 2023+ revival, SSTV is used to transmit terminal screenshots:
- **AS32 code 3#** → Green Terminal (The Rock, Room 101)
- **AS32 code 10#** → Amber Terminal (The Rock, Room 104)
- **AS32 code 11#** → Red Terminal (J's personal terminal)
- **AS32 code 238018300–238018399** → Extended SSTV range

---

## Technical Notes

- SSTV was decoded using standard amateur radio SSTV software (e.g., MMSSTV, RX-SSTV)
- Most original-run SSTV used Scottie 2 mode (8 seconds per image)
- Images show real locations — used to confirm the geographic authenticity of drops
- Community members verified locations via Google Street View / satellite imagery
