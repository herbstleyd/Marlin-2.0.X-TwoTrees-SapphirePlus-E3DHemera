# Marlin-2.0.X-TwoTrees-SapphirePlus-E3DHemera
One functional Marlin 2.0.X Firmware for the TwoTrees Sapphire Plus with E3D Hemera Direct Extruder

**This Marlin Firmware works for the TwoTrees Sapphire Plus (V3: MKS Robin Nano V1.2 with TMC2225 Stepperdrivers on all 5 Ports, one Z-Endstop, two Z-Motors with Belt-Sync and 180 degree rotated display.**
I made changes for the E3D Hemera Setup:
- Because the MKS Robin Nano works with 32 Microsteps i choose 816 E-Steps 160 X-Y Steps (Sap.h) - (For E3D Hemera) - If you can tell me how to set the Robin Nano to 16 microsteps i will be very pleased!
- Thermistor is set to "5" (ATC Semitec 104GT-2/104NT-4-R025H42G - Configuration.h) - (For E3D Hemera)
- Heater_0_maxtemp set to 300 (Configuration.h) - (For E3D Hemera)
- Linear Pressure Control is deactivated (Configuration_adv.h)
