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
