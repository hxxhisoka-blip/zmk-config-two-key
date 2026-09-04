# Build Status

The two-key ZMK source configuration is complete for the confirmed hardware:

- Board: Seeed Studio XIAO nRF52840, regular version
- Shield: `two_key`
- Key 1: XIAO D0 to switch to GND, sends Ctrl+C
- Key 2: XIAO D1 to switch to GND, sends Ctrl+V
- Target: Windows over USB or Bluetooth HID

This workspace does not currently contain the ZMK compiler/toolchain and is
not authenticated to a GitHub account. Therefore a compiled `.uf2` cannot be
verified or honestly included until a ZMK build is run.
