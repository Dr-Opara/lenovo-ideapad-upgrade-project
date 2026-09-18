# 05 - SSD Upgrade

## Goal

Add a 1 TB M.2 NVMe SSD while keeping the original ~512 GB system drive in place.

## New SSD

The selected secondary drive is a **KingSpec NX Series 1 TB NVMe SSD**.

### Identified specifications from the installed part

- Brand: KingSpec
- Series: NX
- Capacity: 1 TB
- Form factor: M.2 2280
- Interface: NVMe
- Part number: NX-1TB 2280
- Intended role: Secondary internal storage

A photo of the new SSD was captured before installation and will be added to the project image set as the SSD reference photo.

## Why keep the original SSD?

The original SSD contains Windows, applications, settings, and personal files. Simply removing it does not erase the data, but the laptop would no longer have access to those files until the drive is reinstalled.

Keeping it installed avoids:

- reinstalling Windows
- cloning the system drive
- restoring applications
- moving existing files

## Installation notes

The new KingSpec SSD must be installed in the correct M.2 slot and secured with the appropriate retaining screw.

Do not force an M.2 NVMe SSD into unrelated storage connectors.

## Windows initialization

If Windows does not immediately show the new SSD in File Explorer:

1. Open Disk Management.
2. Initialize the disk as GPT if prompted.
3. Create a New Simple Volume.
4. Format as NTFS.
5. Assign a drive letter.

## Post-install verification

After reassembly and boot, confirm:

- the original Windows SSD is still detected
- the new KingSpec 1 TB SSD is detected
- the new SSD can be initialized and formatted
- the system boots normally

## Project photo log

Planned repository location:

- `images/ssd-install/kingspec-nx-1tb-before-install.jpg`
- `images/ssd-install/kingspec-nx-1tb-installed.jpg`
