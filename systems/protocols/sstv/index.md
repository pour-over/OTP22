# SSTV — Slow-Scan Television

*Standard image transmission protocol used for drop location images and terminal screenshots.*

---

## Overview

**SSTV** (Slow-Scan Television) is a standard method for transmitting still images over audio channels — originally developed for amateur radio operators. OTP22 uses it extensively for transmitting:
- Images of dead drop locations (to guide players to the physical drop)
- Screenshots of Emtanon terminal displays
- Operational imagery

---

## How SSTV Works

SSTV encodes image data as audio frequencies. A receiver with the appropriate software decodes the audio back into an image. The process is slow (hence "slow scan") — a typical image takes 30–120 seconds to transmit.

**Common SSTV modes used in OTP22:** Martin 1, Martin 2, Scottie 1, Scottie 2 (community-identified; see otp22.org for specifics)

---

## SSTV in OTP22

### Original Run
- Agent codes `68700–68799`: SSTV image range (24 calls logged)
- Agent codes `891038117–118`: Another SSTV range (4 calls)

Images transmitted via this range included photographs of drop locations, guiding players to retrieve physical objects.

### Revival Era
- AS32 code `3#` → Green Terminal screenshot
- AS32 code `10#` → Amber Terminal screenshot
- AS32 code `11#` → Red Terminal screenshot
- AS32 codes `238018300–238018399` → SSTV image range

Terminal SSTV was the primary way players could see what was displayed on Emtanon's terminals before the web portal was established.

---

## Decoding Equipment

To receive SSTV images from the phone system:
1. Call the agent system
2. Enter the SSTV code
3. Hold the phone near a microphone connected to a computer
4. Use SSTV decoding software (e.g., MMSSTV, RX-SSTV, or fldigi)
5. Receive the image

---

## PSK31 and Drop Coordinates

A related encoding method: **PSK31** (Phase-Shift Keying, 31.25 baud) was used in at least one case to encode drop coordinates in what appeared to be instrumental music. The Blyind Tucson drop is associated with this method.

---

## Archive

All recovered SSTV images from both eras are archived at:
- otp22.org (wiki, under SSTV messages)
- Original run images: http://303.sashahart.net/messages/sstv
