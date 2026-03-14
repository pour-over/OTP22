# SHIP Messages — Coordinate Archive

**Source:** http://303.sashahart.net/messages/ship
**Map:** http://303.sashahart.net/messages/ship/map
**Total messages:** 128 entries
**Encoding:** Numbers spoken as ASCII → decoded to SHIP format
**Primary agent code:** 8888 (226 calls logged)

---

## About SHIP Messages

SHIP messages give real-time coordinates of vessels in the OTP22 universe, primarily in the Arctic Ocean near the Bering Strait / Chukchi Sea region. The format is:

```
SHIP [vessel_name] [latitude] [longitude] NOWAT [HH:MM]\
```

Or for aircraft/troops:
```
AIRCFT [id] [lat] [lon] REQAT [HH:MM]\
TROOP [id] [lat] [lon] REQAT [HH:MM]\
AGENT [id] [lat] [lon] REQAT [HH:MM]\
SUPPLY [id] [lat] [lon] REQAT [HH:MM]\
MIG [id] [lat] [lon] NOWAT [HH:MM]\
BOGIE [id] [lat] [lon] NOWAT [HH:MM]\
```

Messages end with `MSG*[agent_code]\` referencing additional information.

---

## Known Vessels

| Vessel | Role |
|--------|------|
| BREAKER1, BREAKER2 | Icebreaker ships clearing path |
| ESCORT | Escort/protection vessel |
| MELTER1, MELTER2, MELTER3, MELTER4 | MELTR fleet — core operational ships |
| MELTR1, MELTR2, MELTR4 | Revival-era naming |
| PETR | Transport/support vessel |
| TRANSP | Main transport ship |
| PAYLD1, PAYLD01 | Payload delivery ship |
| SHADOW | Shadow/covert vessel |

---

## Selected Coordinate Log

### Undated — First SHIP Messages (Bering Strait, ~78°N)

```
SHIP BREAKER1  78.3816 -168.6008  NOWAT 19:00
SHIP BREAKER2  78.4427 -168.6003  NOWAT 19:00
SHIP ESCORT    78.4504 -168.5992  NOWAT 19:00
SHIP MELTER1   78.4593 -168.5502  NOWAT 19:00
SHIP MELTER2   78.2738 -168.6506  NOWAT 19:00
SHIP PETR      72.4096 -166.6177  NOWAT 19:00
SHIP PAYLD1*DEPLOYED* 65.7376 -168.9001 NOWAT 19:00
MSG*2896
```
*Fleet clustered near 78°N, 168°W — Chukchi Sea, north of Bering Strait*
*PAYLD1 deployed ~200 miles south at 65.7°N — near Nome, AK area*

### Undated — Hour-by-Hour Tracking

The fleet moved steadily northward over a 24-hour period:

| Time | BREAKER1 lat | Notes |
|------|-------------|-------|
| 18:00 | 78.2769°N | |
| 19:00 | 78.3816°N | |
| 20:00 | 78.4863°N | |
| 21:00 | 78.5932°N | |
| 22:00 | 78.6997°N | Approaching 79°N |

---

### 2012-09-11 — Early Undated (Bering Strait region)

```
SHIP BREAKER1  64.3376  -168.5994  NOWAT 23:55
SHIP BREAKER2  64.3023  -168.5997  NOWAT 23:55
SHIP ESCORT    64.2862  -168.6005  NOWAT 23:55
SHIP MELTER1   64.2832  -168.5505  NOWAT 23:55
SHIP MELTER2   64.2523  -168.6493  NOWAT 23:55
SHIP MELTER3   64.0  -168.5495     NOWAT 23:55
SHIP PAYLD01   65.2826  -168.5499  NOWAT 23:55
MIG BOGEY1     65.2824  -168.5504  NOWAT 23:55
MIG BOGEY2     65.2828  -168.5302  NOWAT 23:55
```
*Three MELTER ships. MIG BOGEYs present — military aircraft intercept event?*

---

### 2012-09-17 — Fleet Tracking at 79°N

```
SHIP BREAKER1  79.8594  -168.6003  NOWAT 09:08
SHIP BREAKER2  79.9323  -168.5993  NOWAT 09:08
SHIP ESCORT    79.9430  -168.6003  NOWAT 09:08
SHIP MELTER1   79.9534  -168.5500  NOWAT 09:08
SHIP MELTER2   79.7487  -168.6494  NOWAT 09:08
SHIP PETR      72.4096  -166.6178  NOWAT 09:08
SHIP PAYLD1*DEPLOYED* 65.7376  -168.9001  NOWAT 09:08
MSG*2896
```
*Fleet now at ~79-80°N, approaching Arctic Ocean proper*

---

### 2012-09-23 — TRANSP Sighting (Atlantic/Mid-Ocean)

```
SHIP TRANSP  53.9582  -18.8414  NOWAT 00:29
```
*TRANSP at ~54°N, 18°W — mid-Atlantic, west of Ireland, heading toward Arctic*

---

### Later Messages — Svalbard Area (Norwegian Arctic)

```
SHIP PETR   73.4344   13.1525  NOWAT 09:25
SHIP ESCORT  6.4065   76.449   NOWAT 09:25
SHIP MELTR2  6.3956   76.4111  NOWAT 09:25
SHIP MELTR1  6.4054   76.4734  NOWAT 09:25
SHIP MELTR4  6.321    76.458   NOWAT 09:25
```
*PETR at 73°N, 13°E — Svalbard/Bear Island area*
*MELTR fleet at ~6°N, 76°E — **Note: these coordinates appear to be Indian Ocean / Arabian Sea** — possibly a different operation or coordinate format*

---

### Undated — AGENT/TROOP/SUPPLY Grid

Early messages before the fleet-tracking format also gave grid positions for troops, aircraft, and agents:

```
AGENT  30088   72.6347  -114.7938  REQAT 18:53
AIRCFT 64798   30.4600  -121.7647  REQAT 21:46
TROOP  17873   26.4334   -70.3727  REQAT  5:31
TROOP  11329   55.9978   -94.2944  REQAT 10:38
AIRCFT 81543   37.8828   -81.6460  REQAT 19:41
TROOP  27575   48.5250  -119.8109  REQAT  9:30
SUPPLY 99548   37.8197   -83.5826  REQAT  7:29
TROOP  78032   35.8471   -71.5642  REQAT  4:30
AIRCFT 60081   38.7630  -119.1617  REQAT 10:33
TROOP  10179   73.1576  -102.5694  REQAT 18:42
AGENT  33878   30.3495  -113.8797  REQAT  6:22
SUPPLY 11334   35.6246  -100.2318  REQAT 23:52
```
*Scattered across North America — domestic operation grid?*

---

## Geographic Analysis

**Primary operational zone:** Chukchi Sea / Bering Strait (approximately 65–80°N, 165–170°W)

**Fleet trajectory (2012):**
- Started ~65°N (south of Bering Strait)
- Moved north through the Bering Strait
- Reached 80°N by September 2012
- Heading toward the Svalbard Vault (80.3886°N, 5.6538°E per decoded message 48902716041)

**PAYLD1 position:** Consistently at 65.7376°N, 168.9001°W while fleet moved north — suggests PAYLD was staged/anchored at the Bering Strait while MELTR fleet broke ice ahead.

**TRANSP trajectory:** Mid-Atlantic in late 2012, heading northeast toward the Norwegian/Barents Sea and ultimately Svalbard.

---

## Map Resource

Interactive map at http://303.sashahart.net/messages/ship/map
(All coordinates plotted with vessel names and timestamps)

---

*All audio: http://dialer.otp22.com/ — Agent 8888 recordings*
*Encoding: numbers spoken in TTS → ASCII → vessel format*
