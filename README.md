# Raspberry Pi 400 — OctoPi 3D Printer Management

**Brian Emerson · Independent project · 2020–2024 · Retired**

## Overview

I configured a Raspberry Pi 400 running OctoPi to manage a Creality CR-10S and a Snapmaker A350. I could switch between the two printers, operating one at a time. The setup supported uploading and starting prints, camera monitoring, timelapses, and additional features.

This repository documents that earlier project retrospectively in October 2026. It records my hands-on experience; it is not a distribution of OctoPi or a recovered copy of the original configuration.

## Equipment and software

| Component | Role |
|---|---|
| Raspberry Pi 400 | Host for the OctoPi setup |
| OctoPi / OctoPrint | Browser-based printer management |
| Creality CR-10S | More manually operated printer; later upgraded with a BLTouch |
| Snapmaker A350 | Alternative printer managed through the setup |
| BLTouch | Bed-leveling probe added to the CR-10S |

## What I implemented

- Configured OctoPi on a Raspberry Pi 400.
- Used the setup with both printers, switching between them rather than operating both simultaneously.
- Uploaded and started prints through the print-management workflow.
- Used camera monitoring and timelapses.
- Extended the setup with additional features.
- Added a BLTouch bed-leveling probe to the Creality CR-10S.

Specific plugin names, software versions, camera hardware, and BLTouch firmware details have not been reconstructed, so they are not listed as verified configuration.

## Practical experience

The project combined a Raspberry Pi software environment with physical printer hardware. It involved configuring the management interface, working with two different printers, and extending a more manual printing workflow with monitoring and hardware improvements.

The BLTouch upgrade was a separate hardware improvement to the CR-10S. It is included here as part of the wider printing setup rather than presented as an OctoPi feature.

**Skills demonstrated:** Raspberry Pi configuration, OctoPrint use, hardware/software integration, 3D-printer operation, hardware upgrades, and troubleshooting.

## Timeline

| Period | Milestone |
|---|---|
| 2020 | Project began |
| 2020–2024 | Used and expanded the printer-management setup |
| 2024 | OctoPi project retired |
| October 2026 | Project documented retrospectively; Pi 400 repurposed for a separate Pi-hole project |

## Evidence and documentation status

This account is based on my recollection of the completed project. Original screenshots, configuration exports, plugin lists, and print logs are not currently included. Any recovered evidence can be added later with its original date and context.

Project dates describe when I did the work. Repository commits describe when I documented it.

## Related project

The same Raspberry Pi 400 was later repurposed for [Home Network Security — Pi-hole](https://github.com/bemerson24/raspberry-pi-pihole). That is a separate project with a different purpose and timeline.
