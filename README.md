<h1 align="center">PI-Arduino-CAN-Bus</h1>
<p align="center">Reads CAN Protocol using CAN Bus Shield on Arduino parsing it through Serial for the Pi</p>

---
## TLDR
Uses **Arduino R4 Minima** and **Raspberry Pi 3B+** to recieve information about a cars information using the **CAN protocol**. The Arduino in this case handles the CAN parsing and the Pi is the graphical interface for the car.

---

## Why use PI and Arduino instead of one or the other?
It's true that you can use one over the other in my case I already owned an Arduino for the initial project. Initially it was going to be an Arduino with the CAN Bus Shield and an OLED screen to display information fetched from the car's ECU. I was creating a concept of how to gather everything together into a case all while being inside my car, then I realized I can stuff the Arduino and everything else alongside it's component inside a storage bin I have (Radio unit above & Storage bin below). So, I opted in on buying a PI and 7" Screen to display information parsed through the Arduino into the PI. This leaves memory fetching to the Arduino and graphical display to the PI.

---
## What was used?
- Buck DC-DC converter 12V → 5V
- Circuit Fuse Tap
- OBD-2 to DS9/DE9 Cable
- 7" Touchscreen Display
- Raspberry Pi 3B+
- Arduino UNO R4 Minima
- Sparkfun CAN Bus Shield
