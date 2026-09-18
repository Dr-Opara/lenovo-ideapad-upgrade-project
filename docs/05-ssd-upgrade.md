# 05 - SSD Upgrade

## Goal

Add a 1 TB M.2 NVMe SSD while keeping the original ~512 GB system drive in place.

## Why keep the original SSD?

The original SSD contains Windows, applications, settings, and personal files. Simply removing it does not erase the data, but the laptop would no longer have access to those files until the drive is reinstalled.

Keeping it installed avoids:

- reinstalling Windows
- cloning the system drive
- restoring applications
- moving existing files

## Installation notes

The new drive must be installed in the correct M.2 slot and secured with the appropriate retaining screw.

Do not force an M.2 NVMe SSD into unrelated storage connectors.

## Windows initialization

If Windows does not immediately show the new SSD in File Explorer:

1. Open Disk Management.
2. Initialize the disk as GPT if prompted.
3. Create a New Simple Volume.
4. Format as NTFS.
5. Assign a drive letter.
