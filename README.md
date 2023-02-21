These are the files you need to configure Marlin 2.1.2.0 for the BIGTREETECH SKR-mini-E3 V2 and the TFT35 E3 V3.0 Touch Screen for the Ender 3 Pro

Instructions: 
1) Download or Clone the Marlin 2.1.2.0 branch from here --> https://github.com/MarlinFirmware/Marlin/tree/2.1.x
2) Download the platformio.ini file and put that in the main folder.
3) Download the .h files and put them in the Marlin subfolder.
4) Compile with PlatformIO

Notes on this configuration:
The Extruder and Z-axis stepper motors are 90º stepper motors with the voltages adjusted for these motors.
I have a Keenovo AC silicone mats for the bed heater and the Bed Thermistor is set to 11 for this. 
I have a CR-Touch probe and have this configured along with Unified Bed Leveling (UBL).
I started this with the default Marlin config and added the changes recommended by Big Tree Tech (BTT) for the Mini E3 V2 and the TFT35 V3 touchscreen.
I have also made numerous tweaks to this over time (and versions).
