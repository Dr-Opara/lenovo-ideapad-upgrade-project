# 06 - Post-Install Validation

After the hardware installation is complete, validate both memory and storage.

## SSD validation milestone

Windows Disk Management successfully detected the new KingSpec 1 TB NVMe SSD as:

- Disk 1
- Basic
- 953.85 GB usable capacity
- Online
- Initially unallocated

The original Samsung system SSD remains present as Disk 0 with the Windows C: partition intact.

The New Simple Volume Wizard was started for Disk 1. Recommended formatting settings:

- File system: NTFS
- Allocation unit size: Default
- Volume label: 1TB SSD (or Data)
- Perform a quick format: Enabled
- File and folder compression: Disabled

After completing the wizard, the new SSD should receive a drive letter such as D: and appear in File Explorer under This PC.

## RAM checks

Open:

Task Manager -> Performance -> Memory

Confirm:

- approximately 32 GB installed
- expected memory speed
- both memory slots detected

## SSD checks

Open:

Disk Management

Confirm:

- original system SSD is still present
- new 1 TB SSD is detected
- new SSD is initialized and formatted
- new SSD appears in File Explorer with a drive letter

## Optional benchmarks

Capture before/after results for:

- memory usage under normal workload
- Windows startup responsiveness
- application launch times
- SSD sequential read/write performance
- multitasking performance


## File Explorer validation completed

The new KingSpec 1 TB SSD is now fully initialized, formatted, assigned drive letter **D:**, and visible in Windows File Explorer.

Observed final storage layout:

- **1TB SSD (D:)** — 953 GB free of 953 GB
- **Windows-SSD (C:)** — 140 GB free of 475 GB

This confirms that both internal NVMe drives are active at the same time and that the original Windows installation remains intact on the Samsung system SSD.

Status: **SSD upgrade successfully validated in Windows.**


## RAM validation completed

Windows Task Manager successfully detected the upgraded memory configuration:

- Installed memory: 32.0 GB DDR4
- Usable memory: 31.8 GB
- Speed: 3200 MT/s
- Slots used: 2 of 2
- Form factor: SODIMM
- Hardware reserved: 217 MB

This confirms that both Timetec 16 GB modules are installed correctly and operating at the expected DDR4-3200 speed.

Status: **RAM upgrade successfully validated in Windows.**
