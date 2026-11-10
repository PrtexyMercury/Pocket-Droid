# Pocket Droid

A pocket-sized, 3D-printed R2D2-style companion droid designed for autonomous tracking, expressive interactions, and portable utility. Built as part of the **Hack Club Fallen** hardware program.

## Features
* **Custom Enclosure:** Designed in Onshape with a robust 4mm wall thickness, optimized for 3D printing in PLA/PETG.
* **Custom PCB:** A fully routed, compact printed circuit board designed in EasyEDA (`PCB_4th-Attempt`).
* **Expressive Face:** Dual round LCD display modules acting as animated robot eyes.
* **Precise Navigation:** Powered by twin TT DC gear motors with a rear balancing caster and a VL53L0X Time-of-Flight (ToF) laser distance sensor.
* **Audio Feedback:** Miniature passive buzzer for classic droid chirps and alerts.

##  Bill of Materials (BOM)

| Item | Description | Qty | Est. Cost (ZAR) | Supplier |
| :--- | :--- | :---: | :---: | :--- |
| **ESP32 Microcontroller** | ESP32-DEV-38PIN WiFi/BLE Board | 1 | R135.00 | Micro Robotics / Communica |
| **Round LCD Display** | GC9A01 1.28/0.71-inch SPI TFT Eyes | 1 | R220.00 | AliExpress / Local Maker Shop |
| **TT DC Gear Motors** | Dual-shaft DC gear motors | 2 | R60.00 | Next Dimension Electronics |
| **Motor Driver** | Mini Dual-Channel DC Motor Driver | 1 | R45.00 | DIYElectronics / Communica |
| **Caster Wheel** | Rear balancing ball caster | 1 | R15.00 | Local Robotics Store |
| **LiPo Battery** | 3.7V 2000mAh Lithium Polymer Battery | 1 | R180.00 | SR Components |
| **Laser Distance Sensor** | VL53L0X Time-of-Flight ToF Sensor | 1 | R140.00 | Micro Robotics |
| **Passive Buzzer** | Mini 5V/3.3V PCB Mount Buzzer | 1 | R15.00 | Communica |
| **Custom PCB** | JLCPCB Prototype PCB Fabrication | 1 | R100.00 | JLCPCB |
| **3D Printing Filament** | PLA/PETG Shell Material | 1 | R50.00 | Local Stock |
| **Total Estimated Budget** | | | **~R960.00 ZAR** | |

## Repository Structure
* **CAD**: Onshape 3D models and exported STL files for the droid shell.
* **PCB**: EasyEDA source files and production-ready Gerber `.zip` package (`Gerber_PCB_4th-Attempt.zip`).
* **Firmware**: ESP32 control scripts and sensor integration code.
* **`bom.csv`**: Complete parts list and pricing inventory.

## Fabrication & Assembly
1. **Chassis:** 3D print the Onshape shell using PLA/PETG at 0.2mm layer height and 20–30% infill.
2. **Electronics:** Solder components onto your custom EasyEDA PCB and connect the ESP32, VL53L0X sensor, motor driver, and display modules.
3. **Assembly:** Drop components into their respective chassis pockets for a secure, clean fit.

## Design & Previews
* **CAD Model:**
![CAD Screenshot](Screenshot%2026-11-10%205544.png)
