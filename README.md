# Drone CAD Files — SAFMC 2026 (Man-Machine Category)

CAD files for our competition drone built for the 2026 Singapore Amazing Flying Machine Competition (SAFMC), Man-Machine category.

<img width="1280" height="720" alt="photo_2026-04-18_21-35-43" src="https://github.com/user-attachments/assets/de6ec490-d580-440f-9f00-45dea1679144" />

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
| Total Weight | ~2kg |
| Payload Capacity | 400g (total under 2kg limit) |
| Payload Mechanism | Rotating drum with servo + 3:1 gear ratio |
| Payload Attachment | Electromagnets (pick & release) |
| Camera Stabilisation | Gimbal mounted |

---

## Frame Design

The frame was designed from scratch and 3D printed in ABS, built specifically around the rotating drum payload mechanism. Generative modelling techniques and topology optimisation were applied to the frame geometry, reducing overall structural weight by approximately **50%** while maintaining the required rigidity for flight loads.

---

## Payload Mechanism

The payload system uses a **rotating drum** controlled by a servo motor through a **3:1 gear ratio**, allowing precise rotation control. **Electromagnets** are used to attach and release payloads, enabling the drone to:

1. Pick up a payload
2. Rotate the drum
3. Attach a second payload
4. Deliver and release on command

This allows the drone to carry and swap multiple payloads in a single flight.

**Payload Operation**

[![Payload Operation](https://img.youtube.com/vi/4q10erNs9o4/0.jpg)](https://youtu.be/4q10erNs9o4)

---

## Prototypes

Initial prototypes and frame iterations are documented in this repository, showing the evolution of the design from early concepts to the final competition build.

<img width="1280" height="1238" alt="photo_2026-04-18_21-35-46" src="https://github.com/user-attachments/assets/c9f07a71-94c8-4823-b9bf-6d192587f7fc" />

---

**Drone in Flight**

[![Drone Flying](https://img.youtube.com/vi/34dTOgnVPvQ/0.jpg)](https://youtu.be/34dTOgnVPvQ)

---
*Built for SAFMC 2026 — Singapore Amazing Flying Machine Competition*
