<h1 align="center">PI-Arduino-CAN-Bus</h1>
<p align="center">Reads CAN Protocol using CAN Bus Shield on Arduino parsing it through Serial for the Pi</p>

---
## TLDR
Uses **Arduino R4 Minima** and **Raspberry Pi 3B+** to recieve information about a cars information using the **CAN protocol**. The Arduino in this case handles the CAN parsing and the Pi is the graphical interface for the car.

---

## Why use PI and Arduino instead of one or the other?
It's true that you can use one over the other in my case I already owned an Arduino for the initial project. 

> Initially it was going to be an Arduino with the CAN Bus Shield and an OLED screen to display information fetched from the car's ECU. 

While I was concepting how to gather everything together into a one big device, all while being inside my car, I realized I can stuff the Arduino and everything else alongside inside a storage bin I have. 

> My dash kit is Double-DIN. I currently have a radio on one unit and a storage bin below it. For this project I had to swap it around. 

So, I opted in on buying a PI and 7" Screen to display information parsed through the Arduino into the PI. <ins>This leaves memory fetching to the Arduino and graphical display to the PI</ins>.

---
## What was used?
- [Buck DC-DC converter 12V → 5V](https://www.amazon.com/dp/B087RHWTJW?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)
- [Circuit Fuse Tap](https://www.autozone.com/electrical-and-lighting/fuse-and-accessories/p/bussmann-circuit-fuse-tap/547344_0_0)
- [OBD-2 to DS9/DE9 Cable](https://www.sparkfun.com/obd-ii-to-de9-cable.html)
- 7" Touchscreen Display
- [Raspberry Pi 3B+](https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/)
- [Arduino UNO R4 Minima](https://store.arduino.cc/products/uno-r4-minima)
- [Sparkfun CAN Bus Shield](https://www.sparkfun.com/can-bus-shield.html)
