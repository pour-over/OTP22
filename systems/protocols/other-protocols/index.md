# Other Audio Protocols

*TAMI, M6, M7, Bell 103, PSK31, ITA2, BPSK31*

---

## TAMI

A custom audio data protocol. Community decoder exists at https://otp22.org/tools/.

Details of modulation scheme, usage context, and fully decoded TAMI messages are documented on the otp22.org wiki. TAMI appears to be distinct from ABISM — different signal characteristics, different context in the game.

---

## M6

Custom audio protocol. Community decoder exists at https://otp22.org/tools/.

---

## M7

Custom audio protocol. Community decoder exists at https://otp22.org/tools/.

---

## Bell 103

**Standard protocol.** Bell 103 is a 300-baud FSK modem standard from the early 1980s.

In OTP22 (revival), AS32 code `2` provides Bell 103 telemetry — system status data transmitted at 300 baud. A standard Bell 103 modem or software decoder can receive this data.

This is consistent with Emtanon's in-universe 1970s/80s technology aesthetic.

---

## PSK31 (BPSK31)

**Standard protocol.** Phase-Shift Keying at 31.25 baud — a narrow-bandwidth HF digital mode originally designed for amateur radio.

Used in OTP22:
- A BPSK31 message was received on `3033090004` on 2012-09-17 (secondary number discovery)
- PSK31 encoding was used to hide drop coordinates in what appeared to be instrumental music (Blyind Tucson drop)

---

## ITA2

**Standard protocol.** International Telegraph Alphabet No. 2 — the encoding used by Baudot/Teletype machines (TTY/TDD).

Used in OTP22:
- 2012-10-18: ITA2 message on `3033090004` from Polish number `48223071061`: *"DEADMANSWITCHTRIPENTRBELLAGENTCODETOREACTIVATEAGENTSYSTEM"*

The use of ITA2 is consistent with the game's teletype/vintage-telecom aesthetic. TDD (Telecommunications Device for the Deaf) payphones use ITA2 and were explicitly part of the game — the Fort Lauderdale airport TDD payphone (`954-359-0332`) was discovered in June 2013.

Robby also listed "TDD" as one of the communication channels that could be used to reach him.

---

## ITA2 Decoder

Community tool: http://bagud.dk/arg/horns/ita2/

---

## HF (High Frequency Radio)

**Standard radio method.** HF (shortwave) radio was referenced as a backup communication channel between TRANSP and HQ in the original run.

Agent code `150120587` ("HF") played long, revealing conversations at specific times — 244 calls logged, making it one of the more-explored special codes.

In the revival, shortwave transmissions are listed as an **undiscovered system** — the puppetmaster has indicated that 0 transmissions have been received, meaning this channel is still unexplored. A shortwave receiver and knowledge of the appropriate frequencies would be required.

---

## MXP20 (Custom Processor)

Not a communication protocol but a custom processor architecture. The Emtanon terminals and potentially the MELTR ships run on MXP20. Machine code can be uploaded via AS32 code `55559`.

See [terminals/index.md](../../terminals/index.md) for context.
