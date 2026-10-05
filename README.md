# Circuit Design — Practical Exercise

## Overview

This repository contains the completed work for the 2026 Practical Exercise on Circuit Design and ESP32 Schematics. The exercise uses EasyEDA for schematic design and includes circuit calculations, component tables, and an ESP32 microcontroller connected to a DHT22 temperature and humidity sensor.

## Repository Contents

| File | Description |
|---|---|
| `Part-A-Calculations.pdf` | Calculations for the series and parallel circuits, including total resistance, total current, current through each resistor, voltage drops, and power dissipated. |
| `Part-B-Series-and-Parallel-Circuits.pdf` | EasyEDA schematics and component tables for Circuit (a) — series — and Circuit (b) — parallel. |
| `Part-B-ESP32-DHT22.pdf` | EasyEDA schematic and component table for the ESP32–WROOM-32 with DHT22 / AM2302 temperature and humidity sensor. |

## Circuit Summary

### Circuit (a) — Series
- Power supply: 125 V DC
- R1 = 20 Ω, R2 = 30 Ω, R3 = 50 Ω
- Total resistance: 100 Ω
- Total current: 1.25 A
- Voltage drops: 25 V, 37.5 V, 62.5 V
- Power dissipated: 31.25 W, 46.875 W, 78.125 W

### Circuit (b) — Parallel
- Power supply: 125 V DC
- R4 = 20 Ω, R5 = 100 Ω, R6 = 50 Ω
- *(Parallel calculations to be inserted once Part A is finalized.)*

### ESP32 + DHT22
- U1: ESP32-WROOM-32 Microcontroller
- S1: DHT22 / AM2302 Temperature and Humidity Sensor
- R1: 10 kΩ resistor (ESP32 EN pull-up)
- R2: 10 kΩ resistor (DHT22 data pull-up)
- C3: 100 nF decoupling capacitor
- Power supply: 3.3 V DC

## Group Contributions

- **Member 1 — Makutano Basile Musavuli** Series circuit calculations, schematic, and component table.
- **Member 2 — Amos Sifa** Parallel circuit calculations, schematic, and component table.
- **Member 3 — Princeroy Mwangi** ESP32–DHT22 schematic design in EasyEDA.
- **Member 4 — Allan Bundi** Component table and DHT22 wiring verification against the datasheet.
- **Member 5 — Abdwilly Hassan** Schematic review, EasyEDA design checks, error correction, and PDF export.
- **Member 6 — Ramla Abdullahi Dimbil** Compilation of Part A and independent verification of the circuit calculations.
- **Member 7 — Ibrahim Hamza Saleh** GitHub repository creation, collaborator management, document publishing, README preparation, and submission coordination.

## Tools and References

- **EasyEDA** — circuit schematic design.
- **DHT22 datasheet** — sensor wiring and supply requirements.
- **Practical exercise brief** — reference schematic and instructions.

## Notes

- All submitted calculations and schematics have been checked for accuracy and completeness before final submission.
- The repository is public so the lecturer can access it directly.
- The link to this repository was submitted on eLearning before the deadline.

## Repository Link

https://github.com/HamzaSaleh-Cyber/Circuit-Design
