# BW16 PCB for Nova-X 5G Deauther

> **This is not the official repository.** This is a fork of the official Nova-X 5G Deauther firmware project, focused on providing a custom PCB design for the **BW16** variant (not the C5 version).

Official firmware repository: [warwick320/Nova-X-5G-Deauther](https://github.com/warwick320/Nova-X-5G-Deauther)

---

## Overview

This repository contains the hardware design files for a custom PCB built around the **Realtek BW16** module, intended to run the Nova-X 5G Deauther firmware. The design includes a full schematic and production-ready Gerber files.

---

## Repository Contents

| File | Description |
|------|-------------|
| `NovaX.pdf` | Circuit schematic |
| `NovaX-Gerber.zip` | PCB manufacturing files (Gerber format) |

### Gerber Files (inside `NovaX-Gerber.zip`)

| File | Layer |
|------|-------|
| `NovaX-F_Cu.gbr` | Front copper layer |
| `NovaX-B_Cu.gbr` | Back copper layer |
| `NovaX-F_Mask.gbr` | Front solder mask |
| `NovaX-B_Mask.gbr` | Back solder mask |
| `NovaX-F_Paste.gbr` | Front solder paste |
| `NovaX-B_Paste.gbr` | Back solder paste |
| `NovaX-F_Silkscreen.gbr` | Front silkscreen |
| `NovaX-B_Silkscreen.gbr` | Back silkscreen |
| `NovaX-F_Courtyard.gbr` | Front courtyard |
| `NovaX-B_Courtyard.gbr` | Back courtyard |
| `NovaX-F_Fab.gbr` | Front fabrication layer |
| `NovaX-B_Fab.gbr` | Back fabrication layer |
| `NovaX-Edge_Cuts.gbr` | Board outline |
| `NovaX-PTH.drl` | Plated through-hole drill file |
| `NovaX-NPTH.drl` | Non-plated through-hole drill file |
| `NovaX-job.gbrjob` | Gerber job metadata |

---

## Getting Started

### Viewing the Schematic

Open `NovaX.pdf` with any PDF viewer to inspect the circuit design.

### Ordering the PCB

1. Download `NovaX-Gerber.zip`
2. Upload the zip file directly to your preferred PCB manufacturer (JLCPCB, PCBWay, OSHPark, etc.)
3. Select your preferred stackup, quantity, and finish options
4. Order and wait for delivery

### Bill of Materials

> Component list coming soon.

---

## Target Hardware

- **Module:** Realtek BW16 (RTL8720DN)
- **Firmware:** [Nova-X 5G Deauther](https://github.com/warwick320/Nova-X-5G-Deauther)

---

## Legal Disclaimer

This hardware is intended for **authorized security testing, educational purposes, and network research only**. Sending deauthentication frames on networks you do not own or do not have explicit permission to test may violate local laws (e.g. the Computer Fraud and Abuse Act in the US, or equivalent legislation in your country). **Use responsibly and only on networks you own or are authorized to test.**

---

## License

Hardware design files are shared as-is. Refer to the official firmware repository for its license terms.
