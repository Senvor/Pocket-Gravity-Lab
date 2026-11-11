<div align="center">

# Pocket Gravity Lab

**A physics lab that fits in your pocket.**

A portable, interactive physics laboratory for exploring gravity and orbital mechanics through real-time simulations, physical controls, and embedded hardware.

![Hackatime](https://hackatime.hackclub.com/api/v1/badge/U0B4TE3MN1G/Senvor/Pocket-Gravity-Lab)

</div>

---

> **Status: in progress.** This is an early-stage hardware project. The KiCad project is set up and the schematic has been started, but there's no PCB layout or firmware yet.

## What is it?

Pocket Gravity Lab is a handheld device for playing with gravity and orbits. The plan is to run real-time physics simulations on a small screen and control them with physical buttons and inputs, all on custom embedded hardware.

It's built with C++ and designed for the **Teensy 4.1**.

## Planned Features

- **Real-time simulations** of gravity and orbital mechanics
- **Physical controls** to interact with the simulation
- **Portable embedded hardware**, small enough to carry around

## Where it's at

| Part | Status |
|---|---|
| KiCad project | Set up |
| Schematic | Started: a **Waveshare 2.4" LCD** and a **Teensy 4.1** symbol are placed, not wired up yet |
| PCB layout | Not started |
| Firmware (C++) | Not started |
| Enclosure | Not started |

## Tech Stack

- **KiCad** - schematic and PCB design
- **C++** - firmware (planned)
- **Teensy 4.1** - the target microcontroller

## Project Structure

```
Pocket-Gravity-Lab/
├── Pocket Gravity Lab.kicad_pro   # KiCad project
├── Pocket Gravity Lab.kicad_sch   # schematic (in progress)
├── Pocket Gravity Lab.kicad_pcb   # PCB layout (empty for now)
└── LICENSE
```

## License

This project is licensed under the [MIT License](LICENSE). You're free to use, modify, and share it, as long as the original copyright notice is kept.
