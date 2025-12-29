# Helix

![Helix Keyboard](final.jpeg)
![Helix PCB](helix-front.png)

Helix is a **34-key split wireless keyboard** designed as a compact, ergonomic daily driver.  
It uses a reversible PCB, hot-swap sockets, and runs ZMK firmware on nice!nano controllers.

This repository contains **all hardware, PCB, and mechanical design files** required to build the keyboard.

---

## Features

- 34-key split layout
- Reversible PCB (same PCB for left and right halves)
- Wireless (nice!nano + ZMK)
- Hot-swap MX switches

---

## Repository Structure

### Root
Main KiCad project files:
- `helix.kicad_pcb`
- `helix.kicad_sch`
- `helix.kicad_pro`

### `footprints/`
Custom KiCad footprints used in the PCB.

### `symbols/`
Custom schematic symbols.

### `3d_models/`
STEP / 3D models used for PCB visualization and mechanical checks.

### `case/`
STL files for the keyboard case.

### `gerber/`
Final Gerber files for PCB manufacturing.

---

## Build Guide

A step-by-step build guide is available here:

👉 **[Build Guide](buildguide.md)**

---

## Firmware

Firmware configuration lives in a separate repository:

👉 https://github.com/bgics/zmk-helix

---

## Notes

- This is a **reversible PCB**, so the same PCB is used for both left and right halves.
- Battery size depends on the case — check the STL files before ordering batteries.
