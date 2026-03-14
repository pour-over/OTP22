# 16xxx Messages — Agent Voicemail Archive

**Source:** http://303.sashahart.net/messages/16xxx
**Agent code range:** 16000–16999
**Total calls logged:** 1,280+
**Primary codes:** 16041 (544 calls), 16042 (180), 16043 (173), 16044 (32), 16045 (32)

---

## About 16xxx Codes

The 16xxx range functions as an agent voicemail system. Agents call these codes to receive orders, drop coordinates, and operational instructions. The primary agent mailboxes:

| Code | Agent | Calls |
|------|-------|-------|
| 16001 | AI Bouerges (profile data) | 60 |
| 16002 | Second agent | 39 |
| 16003 | Third agent | 7 |
| 16041 | **AI Bouerges** — primary orders | 544 |
| 16042 | Second agent orders | 180 |
| 16043 | Third agent orders | 173 |
| 16044 | Fourth agent | 32 |
| 16045 | Fifth agent | 32 |
| 16241 | Handshake/upload for 16041 | 33 |
| 16242 | Upload for 16042 | 12 |
| 16243 | Upload for 16043 | 15 |

**16000:** Fast tones (28 calls)
**16041–16045:** Total 961+ combined calls

---

## Message Format

Decoded 16041 messages use the format:
```
/[COMMAND]/[VALUE]/[NOTES]/...
```

Common commands:
- `/ORDERS/` — operational orders
- `/DROP/` — drop location instructions
- `/NOTES/` — additional context
- `/MSG/` — reference to an 18xxx message

---

## Selected Message Archive

### 2012-11-21 — First 16241 Activity
**3033090004 16241**
[wav](https://soundcloud.com/rmmartins/3033090004-wed-nov-21-2012)
*Brief encoded data of some kind*

### 2012-12-13 — First 16041 Orders
**3033090004 16041** (XOR decoded)
[wav](http://dialer.otp22.com/2012-12-13%2007-46%20UTC%20-%20303-309-0004%20-%2016041.wav)
```
/ORDERS/TBD*MSG*18001
```
*Orders to be determined — see message 18001*

### 2012-12-16
```
/ORDERS/TBD*MSG*18001
```

### 2012-12-18
```
/ORDERS/TBD/MSG/NONE/
```

### 2012-12-20
```
/ORDERS/TBD/MSG/18011/
```

### 2013-01-31 — Drop Retrieval Order
**2029993335 16041** (XOR decoded)
[wav](http://dialer.otp22.com/2013-01-31%2018-21%20UTC%20-%20202-999-3335%20-%2016041.wav)
```
/DROP/LOCATION 355/NOTES/DORVINS BACK/NOTES/COLLECT GREEN BOOK IN BAG/NOTES/AVOID BEING SEEN/
```
*"Location 355" — retrieve Green Book from "Dorvin's back" — avoid detection*

### 2013-02-08
**3033090004 16041** (XOR decoded)
[wav](http://dialer.otp22.com/2013-02-08%2004-01%20UTC%20-%20303-309-0004%20-%2016041.wav)
```
/NOTES/PLEASE CONFIRM RECEIPT OF DROP WITH AGENT CODE 99984/N
```
*Post-drop confirmation instruction*

### 2013-01-28 — ABISM Cross-References
**16042 (ABISM):** `468:18027` → references OTP message 18027
**16043 (ABISM):** `468:18101` → references OTP message 18101

### 2013-02-18
**16042:** `468:18053`
**16043:** `468:0004`

### 2013-02-25
**16042:** `Z809331`

### 2013-04-29 — Ft. Lauderdale + SSTV
**16041:** Song → 18084 reference → SSTV image of airport payphones

### 2013-05-08 — NYC Drop
**16043 (Scottie 2 SSTV):** `18087` reference + SSTV image of NYC drop location

### 2013-10-16 — Sebastopol
**16041:** Sebastopol, CA drop coordinates → leads to Cleveland Direct card (held by drawbars)

---

## Extended Agent Codes (160410–160450)

51 calls logged to the range 160410–160450 — suggesting sub-codes for specific agent functions.

---

## The "AI Bouerges" Mystery

Agent 16041 ("AI Bouerges") is the most active agent in the system:
- Profile: Japanese female, born 06/21/84, 157cm, 49kg
- First name "AI" (possibly a pseudonym/callsign)
- Based initially in Playa del Rey, CA, then Las Vegas
- **Disappeared in spring 2013** — J repeatedly asks "WHERE IS SHE?"
- The Smugtrio shipments (April and July 2013) were sent *to* AI Bouerges at her Playa del Rey address
- 16041 continued to give orders after her disappearance, suggesting the account was taken over

The mystery of AI Bouerges' disappearance is one of the unresolved narrative threads of the original run.
