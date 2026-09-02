# Star-Delta Three-Phase Motor Starter (ESP32-C6)

A Star-Delta motor starter running on an ESP32-C6. Written in Arduino C++ using PlatformIO in VSCode.

---

### Story

I originally started this project because I wanted to simulate contactor logic. Real contactors are pretty expensive, so I thought it’d be a fun challenge to recreate the Star-Delta starting sequence entirely in code using cheap components. I wrote the code, tested it on a breadboard using LEDs, and then let the project sit and collect dust for a few months.

Fast forward a bit, I came back to it because I wanted to practice drawing electrical schematics in KiCad, combining microcontroller logic with power and control circuits. 

While writing up this repository and reviewing my final KiCad drawing, I had a sudden epiphany: I had drawn real contactors right back into the control circuit anyway, despite trying so hard to avoid them in the first place. Turns out I built an overengineered microcontroller setup just to drive the very contactors I was running away from. 😅

Even though the final design ended up being completely redundant, it was still a great way to practice writing clean code, drawing electrical schematics and going over basics related to electronics.

---

## Schematic

![Star-Delta Control Schematic](./Star-Delta-Starter.png)
