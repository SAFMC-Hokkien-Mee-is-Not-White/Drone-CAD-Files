# Drone CAD Files — SAFMC 2026 (Man-Machine Category)

CAD files for our competition drone built for the 2026 Singapore Amazing Flying Machine Competition (SAFMC), Man-Machine category.

---

## Overview

This repository contains all CAD files for the drone and payload delivery system developed by our team. The design prioritises weight efficiency, structural rigidity, and a fully autonomous-compatible payload mechanism — all within the SAFMC 2kg total weight limit.

---

## Hardware

| Component | Details |
|---|---|
| Flight Controller | Pixhawk 6C Mini |
| Flight Stack | PX4 |
| Frame | Fully custom 3D printed |
| Total Weight | ~1.6kg |
| Payload Capacity | 400g (total under 2kg limit) |
| Payload Mechanism | Rotating drum with servo + 3:1 gear ratio |
| Payload Attachment | Electromagnets (pick & release) |
| Camera Stabilisation | Gimbal mounted |

---

## Frame Design

The frame was designed from scratch and 3D printed, built specifically around the rotating drum payload mechanism. Generative modelling techniques were applied to the frame geometry, reducing overall structural weight by approximately **50%** while maintaining the required rigidity for flight loads.

---

## Payload Mechanism

The payload system uses a **rotating drum** controlled by a servo motor through a **3:1 gear ratio**, allowing precise rotation control. **Electromagnets** are used to attach and release payloads, enabling the drone to:

1. Pick up a payload
2. Rotate the drum
3. Attach a second payload
4. Deliver and release on command

This allows the drone to carry and swap multiple payloads in a single flight.

---

## Prototypes

Initial prototypes and frame iterations are documented in this repository, showing the evolution of the design from early concepts to the final competition build.

---

## Repository Structure

\```
├── Docking port/
├── Drone_Custom_frame/
├── Drone_F450/
├── Drone_F550/
\```

---

*Built for SAFMC 2026 — Singapore Amazing Flying Machine Competition*

