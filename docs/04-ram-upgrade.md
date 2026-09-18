# 04 - RAM Upgrade

## Existing configuration

The laptop originally had a single 8 GB DDR4-3200 SODIMM installed, leaving the second RAM slot empty.

### Old RAM

- Capacity: 8 GB
- Type: DDR4 SODIMM
- Speed: DDR4-3200
- Configuration: 1 x 8 GB
- Status: Removed during this upgrade

A photo of the original module was captured before replacement and will be added to the project image set as the "old RAM" reference.

## New / upgraded configuration

The replacement kit is a Timetec Premium 32 GB kit consisting of two 16 GB modules.

### New RAM

- Brand: Timetec
- Capacity: 32 GB total
- Configuration: 2 x 16 GB
- Type: DDR4-3200
- PC rating: PC4-25600
- Form factor: 260-pin SODIMM
- Voltage: 1.2 V
- CAS latency: CL22
- ECC: Non-ECC
- Buffered: Unbuffered

A photo of the new Timetec modules was captured before installation and will be added to the project image set as the "upgrade RAM" reference.

## Before vs. after

| Item | Before | After |
|---|---|---|
| Total RAM | 8 GB | 32 GB |
| Module layout | 1 x 8 GB | 2 x 16 GB |
| Memory type | DDR4 SODIMM | DDR4 SODIMM |
| Rated speed | DDR4-3200 | DDR4-3200 |
| Slots used | 1 of 2 | 2 of 2 |
| Channel configuration | Single module | Matched pair / dual-channel capable |

## Installation procedure

1. Shut Windows down completely.
2. Unplug the AC adapter.
3. Remove the laptop bottom cover.
4. Disconnect and physically remove the internal battery.
5. Release the retaining clips holding the original 8 GB RAM module.
6. Remove the original 8 GB module.
7. Insert the first Timetec 16 GB module at an angle, aligning the notch.
8. Press the module downward until both retaining clips lock.
9. Install the second Timetec 16 GB module into the remaining slot.
10. Confirm both modules are fully seated before reconnecting the battery.

## Expected result

- Slot 1: 16 GB
- Slot 2: 16 GB
- Total: 32 GB
- Expected memory speed: DDR4-3200 / 3200 MT/s, subject to system firmware configuration

## Post-install verification

After reassembly and boot:

**Windows Task Manager -> Performance -> Memory**

Verify:

- Approximately 32 GB installed
- Both RAM slots detected
- Memory speed reported at or near 3200 MT/s
- System boots normally with no memory errors

## Project photo log

Planned repository locations:

- `images/ram-install/old-8gb-module.jpg`
- `images/ram-install/new-timetec-32gb-kit.jpg`
- `images/ram-install/ram-slots-before.jpg`
- `images/ram-install/ram-installed-32gb.jpg`
