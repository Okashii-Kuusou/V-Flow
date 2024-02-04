# V-Flow 
A fume extraction system for Voron 2.4 printers.

![](Reference_Images/V-Flow_Cross_Section_View.jpg)
## Introduction
The V-Flow Fume Extraction System is specifically designed for the Voron 2.4 3D printer, offering a practical solution for managing and redirecting ABS/ASA material fumes outside through a 4-inch dryer window vent. This system is engineered for easy assembly, with components that can be printed without supports, simplifying the setup process. The repository also includes additional components aimed at sealing the enclosure and maintaining optimal chamber temperatures, enhancing the overall printing experience.

## Features
- **Direct Fume Extraction:** Routes ABS/ASA fumes outside, ensuring cleaner workspace air.
- **Ease of Assembly:** All components are designed to be printed without the need for supports.
- **Quick Disconnect:** Enables effortless hose detachment for hassle-free maintenance.
- **Adhesive-Free Seal:** Facilitates easy installation and removal, enhancing convenience.
- **Dual Printer Compatibility:** Designed to work seamlessly with a second printer, the system includes the Combined Exhaust Ventilation System (CEVS) for integrating two printers into a single exhaust setup, effectively preventing backflow.

![](Reference_Images/CEVS-Overview.jpg)

# Installation Guide
  - Please follow the detailed steps in the [Installation Guide](Installation_Guide.md) to set up your V-Flow System.


## Prerequisites for V-Flow System Installation
To successfully set up the V-Flow system, the following components are essential:
- **Noctua NF-A6x25 Fan**: This fan is recommended for its efficient airflow and quiet operation. [View on Amazon](https://www.amazon.com/dp/B01K4HRLRI?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- **Dryer Vent Window Kit**: This kit is designed for a 4-inch hose. However, the `Window_Vent_Hose_Adapter.stl`, found in the`Combined_Exhaust_Vent_System` STL folder, modifies this setup to accommodate a 2.5-inch hose. [View on Amazon](https://www.amazon.com/gp/product/B0BXWH53M4/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1).
- **2.5-inch Hose**: This hose connects the printer(s) to the window dryer vent. Note: The hose is available in 10ft lengths; assess your space to determine the required length for your setup. [View on Amazon](https://www.amazon.com/gp/product/B0C85G8P2R/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1).
- **Silicon Mats**: These mats are necessary for crafting one-way valves used with the CEVS. Additionally, adding a valve on the `Window_Vent_Hose_Adapter.stl` for single or dual printer setups can prevent backdraft, though it remains optional. [View on Amazon](https://www.amazon.com/gp/product/B083TKTJS5/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1).


## Recommended/Required Mods
To enhance the performance of the V-Flow system and ensure optimal chamber temperature management, the following modifications are highly recommended:
- **Ellis Bed Fan Mod**: Essential for controlling chamber temperatures. This mod is crucial when using the V-Flow exhaust system. [Ellis Bed Fans Mod](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Bed_Fans).
- **Extrusion End Caps**: My creation, `Extrusion_End_Cap.stl`, available in the `STL_FILES` subfolder `Accessories_&_Tools`, seals gaps at the machine's top, enhancing chamber temperature control.
- **Z-Covers & Z-Plug**: Remixed parts, originals sourced from the internet. These parts seal gaps around the Z motors, specific to the Voron 2.4. Available in the **Accessories_&_Tools** directory.
- **Bed Wiring Grommet by LoCoCNC**: Organizes and protects bed wires, offering a cleaner setup and better seal. [Bed Wiring Grommet](https://mods.vorondesign.com/detail/PNilw0WXR7Qmhquj749iFg).
### Future Enhancements
- **Z Chain Wire Grommet**: An upcoming addition to the `STL_FILES` subfolder  `Accessories_&_Tools` will seal the large hole at the back of the machine. Until then, taping this hole is recommended, similar to sealing bottom panel gaps, for improved chamber temperatures.


## Contributing
  - Contributions are welcome! If you have improvements or bug fixes, please submit a pull request or open an issue.

## License
  - This project is licensed under the [GNU General Public License v3.0](LICENSE).

# Acknowledgements
- The `Voron-Rear_Mounting_Plate.stl` is a remixed component from the umbilical passthrough mod by [whopping_Voron_mods](https://github.com/tanaes/whopping_Voron_mods/tree/main/umbilical_passthrough) The `Voron-M16_Cable_Gland_Housing.stl` stl remains unchanged.
- Inspiration for the one-way valve feature comes from the 2.4 Window Ventilation System available on [TeamFDM](https://www.teamfdm.com/files/file/463-24-window-ventilation-system/).
- The quick connect mechanism was inspired by The Aluminum Carpenter's [YouTube video](https://www.youtube.com/watch?v=LfHVOZGakTQ).

