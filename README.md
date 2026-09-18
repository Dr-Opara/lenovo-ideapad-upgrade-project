# Lenovo IdeaPad Gaming 3 Upgrade Project

This repository documents a real hardware upgrade of a Lenovo IdeaPad Gaming 3 15IHU6 (MTM 82K100L5US).

## Project goals

- Upgrade memory from 8 GB to 32 GB
- Add a 1 TB M.2 NVMe SSD while preserving the existing ~512 GB system SSD
- Document disassembly, installation, validation, and lessons learned
- Capture before/after hardware information and benchmarks

## Original system

- Model: Lenovo IdeaPad Gaming 3 15IHU6
- MTM: 82K100L5US
- CPU: Intel Core i5-11300H
- GPU: NVIDIA GeForce GTX 1650 4 GB
- Original RAM: 8 GB DDR4-3200
- Original storage: ~512 GB SSD
- OS: Windows 11

## Upgrade parts

### Memory
- Timetec Premium 32 GB kit
- 2 x 16 GB
- DDR4-3200
- PC4-25600
- 260-pin SODIMM
- 1.2 V
- CL22
- Non-ECC / unbuffered

### Storage
- 1 TB M.2 2280 NVMe SSD
- Intended use: secondary storage while keeping the original Windows SSD installed

## Current status

Hardware installation is complete. The original 8 GB RAM has been replaced with a matched 32 GB (2 x 16 GB) Timetec DDR4-3200 kit, and the KingSpec NX Series 1 TB M.2 2280 NVMe SSD has been installed. Windows now detects the new SSD as 1TB SSD (D:) with about 953 GB usable space while the original Windows-SSD (C:) remains intact.

## Documentation

See the `docs/` directory for the step-by-step installation log and validation notes.

## Photo plan

Photos from the upgrade will be organized under:

- `images/system-info/`
- `images/parts/`
- `images/disassembly/`
- `images/ram-install/`
- `images/ssd-install/`
- `images/final/`

## Safety note

Power the laptop off fully, unplug the charger, and disconnect/remove the internal battery before installing or removing RAM or storage devices.
