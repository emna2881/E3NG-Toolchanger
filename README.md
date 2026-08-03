# E3NG-Toolchanger
A hotend-swapping toolchanger system modified for the E3NG (Ender-3 NG) 3D printer.

<img width="1624" height="1624" alt="Render" src="https://github.com/user-attachments/assets/b06b8c5e-580d-412d-b851-8f744f4c872c" />

> [!IMPORTANT]
> **Note: This project is currently in Beta. Community testing and feedback are greatly needed.**
> 
> **Some features(BOM, printer.cfg, marcos...) will be updated in a future release.**
## Credits
This project is based on E3NG by RH3D : https://github.com/RH3D/E3NG

Also, I designed mount for Metal Bed of Nudge probe for tool offset calibration. Thanks to zruncho3d for developing Nudge : https://github.com/zruncho3d/nudge

(+) The extruder design for this toolchanger was inspired by Irbis3D's MedusaHC (https://github.com/Irbis3D/MedusaHC). His DuEnder project and its accompanying hotend changer system, MedusaHC, are incredibly sophisticated and highly refined, and they were immensely helpful to me while designing the toolchanger system for the E3NG.

I would like to express my deepest gratitude to Irbis3D for his continuous efforts in advancing the Ender-3. Additionally, I sincerely apologize for the delay in adding this credit.

## Key Features
<img width="5098" height="2475" alt="asdf" src="https://github.com/user-attachments/assets/43d5cb2f-0e59-460a-8155-e4ef3b0e17bc" />

* Hotend-Swapping Mechanism: Swaps hotends while utilizing a single extruder drive gear set and a single pair of part cooling fans, significantly reducing toolhead weight and cost.
* Servo-Driven Cam Arm: Features a servo motor with a cam mechanism that disengages the extruder idler arm to clear the filament path for tool changes.
* Multi-Tool Capacity: Supports up to 6 tools (5 tools recommended for optimal clearance)

## Print Settings and Recommendations

To ensure mechanical strength and thermal resistance, please follow these guidelines when printing the parts:

### Material Selection
* Recommended: ABS or ASA (Best for enclosure heat resistance and structural integrity).
* Acceptable: PETG can be used if you are operating the printer without an enclosure.
* DO NOT USE PLA: PLA is strongly discouraged, especially for the hotend, toolhead, and carriage parts, due to heat deflection issues.

### Print Specifications
* Walls and Infill: Follow the official E3NG recommended print guidelines (e.g., 4 perimeters, 5 top/bottom layers, 30% infill)
* Supports: Most STL files are designed to be printed supportless. However, a few specific components require custom support setups (Detailed support guide will be added in a future update).

## License
This project is licensed under the terms of the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
