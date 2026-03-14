# ABISM Protocol

*Custom modem protocol. One of OTP22's major unsolved technical challenges.*

---

## Overview

**ABISM** is a custom audio data protocol — a modem-like signal — that appears extensively in the OTP22 agent systems. It predates the revival and was present throughout the original run. Decoding it has been one of the community's longest-running technical challenges.

The name "ABISM" is used consistently in internal Emtanon messaging. It appears to be an actual working data protocol, not just flavor.

---

## Where ABISM Appears

### Original Run
- Agent code `**` (double-star): ABISM
- Agent code `37`: ABISM (13 calls)
- Agent code `38`: ABISM (15 calls)
- Agent code `1320`: ABISM MAPS SERVICE (54 calls)
- Agent code range `17000–17999`: ABISM data (412 calls total)
- Agent code `17003`: "ABISM TUNE — ABISM FREQUENCY TONES. TURN THE POTS WITH SCREW DRIVER UNTIL LED LIGHTS UP"

The `17003` description is remarkable: it implies physical hardware with potentiometers (pots) and an LED indicator, suggesting ABISM was designed to interface with a real hardware device that agents would have possessed.

### Referenced in Internal Messages
ABISM is referenced extensively in the 18xxx OTP message archive. Robby (Robert Bramble) in late 2013 explicitly listed ABISM as one of the communication channels players could potentially use to reach him:
> "...X.25, TDD, ABISM, HF, Zeus."

The "VECTORCOM" device (referenced in original run messages) has "ABCD keys" and is mentioned alongside ABISM — it may be the physical hardware the protocol was designed for.

### ABISM MAPS
Agent code `1320` is labeled "ABISM MAPS SERVICE" with 54 calls logged. This suggests ABISM transmitted geographic data — possibly maps or coordinates — in addition to text.

---

## Technical Characteristics

ABISM audio recordings have been captured and analyzed by the community. Key observations:

- Sounds like a modem signal but does not decode with standard modem protocols
- Does not match: Bell 103, Bell 202, V.21, V.22, V.32, DTMF, SSTV, PSK31, or other common protocols
- Appears to be a custom FSK (frequency-shift keying) or similar modulation scheme
- Multiple distinct "variants" have been identified in recordings from different codes

---

## Community Decoder

A community-built ABISM decoder exists at:
**https://otp22.org/tools/**

The decoder was developed through collaborative reverse-engineering of audio samples. Its current capabilities and accuracy are documented on the otp22.org wiki.

---

## ABISM and the AS36 / Hardware Connection

The original run's remote field installation **AS36** ("Alpha Sigma 36") was a battery/solar/radio unit. ABISM appears to be the communication protocol it used. When AS36 went back online after a tape log buffer overflow in May 2014, the Robbybox also returned briefly — suggesting the two systems were linked.

Agent code `17003` text — "TURN THE POTS WITH SCREW DRIVER UNTIL LED LIGHTS UP" — describes calibrating a hardware receiver for the ABISM signal. This means:
1. Real physical ABISM receivers existed (at least one was operational in 2013–2014)
2. The agent system transmitted real ABISM data that a hardware device could decode
3. Drop contents (especially electronic components) may have been ABISM receiver parts

---

## Open Questions

- What is the full modulation scheme?
- What data does the ABISM MAPS service contain?
- Are there complete, undecoded ABISM transmissions from the original run that haven't been processed?
- What did Robert Bramble mean when he said ABISM was a channel to reach him?

See [puzzles/unsolved/index.md](../../puzzles/unsolved/index.md) for current status.
