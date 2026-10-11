starbie -> half life
Starbie: Digital Pet PCB Project

Welcome to my Starbie project :) This is a custom star-shaped digital pet device built with an ESP32 micro-controller, an OLED screen, and a few cool sensors.

Project Overview

- Designed a star-shaped PCB layout in KiCad (`.kicad_pcb`).
- Completed track routing and added a ground (`GND`) pour layer.
- Programmed using Arduino IDE to control the display, buttons, and custom screen animations (including a sparkle trail!).

Repository Contents

- `Starbie.kicad_pcb`: KiCad board layout file
- `Starbie.kicad_sch`: Schematic diagram
- `Starbie.ino`: Arduino code for the digital pet
- `Gerbers/`: Exported Gerber & Drill fabrication files for manufacturing

How It Works

1. Schematic & Routing: Wired components together in KiCad, cleaned up connections, and poured a `B.Cu` ground fill.
2. Fabrication: Exported Gerber files to send off for physical PCB production.
3. Software: Loaded the custom code onto the board to bring Starbie to life!

*Built as part of the Starbie hardware project.*
<img width="193" height="188" alt="Screenshot 2026-10-11 122940" src="https://github.com/user-attachments/assets/023c7c54-9961-4a8a-b86e-0bca05cd5772" />

above is a picture of my starbie in the pcb editor it has been routed and I did a GND pour on it.

