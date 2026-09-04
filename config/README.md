# Two Key Windows Copy Paste

Hardware target: Seeed Studio XIAO nRF52840 (regular, non-Sense).

Wiring:

- Key 1: XIAO D0 to switch to GND
- Key 2: XIAO D1 to switch to GND

The generated firmware sends Ctrl+C and Ctrl+V over USB or Bluetooth HID.

## Firmware build

This is a ZMK configuration repository. `build.yaml` targets the `xiao_ble`
board and the `two_key` shield. The firmware can be built by ZMK's supported
cloud workflow or with a local ZMK toolchain.

The first firmware installation must be flashed over USB-C through the XIAO
UF2 bootloader. No battery is required for the first test.
