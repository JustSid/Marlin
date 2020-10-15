# Overview

This is a fork of [Marlin](https://github.com/MarlinFirmware/Marlin) for my Anycubic Mega X running on an Bigtree Tech SKR 1.4 Turbo with TMC 2209 drivers.

# Modifications

  * Motherboard is set to BOARD_BTT_SKR_V1_4_TURBO
  * Thermistors and other physical attributes of the machine (bed size, homing direction etc)
  * Stepper drivers are set to TMC2209
  * Classic jerk is enabled
  * BLTouch support with 8x8 probing grid
  * Dual Z end stops (the second end stop is on ZMAX (Pin 1.0))

There currently is no support for a display because the default Anycubic touch screen is horrible and I haven't figured out what to replace it with. Running the printer relies completely on OctoPi
