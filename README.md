# V-Flow
A Fume Extraction System made for Voron 2.4 and Trident 3D printers. Enhance your 3D printing environment by safely managing and redirecting fumes outdoors, ensuring a clean and healthy workspace.
![](Reference_Images/V-Flow_Cross_Section_View.jpg)

## Key Features
- **Direct Fume Extraction:** Routes ABS/ASA fumes outside, ensuring cleaner workspace air.
- **Ease of Assembly:** All components are designed to be printed without the need for support using Voron recommended print settings.
- **Quick Disconnect:** Enables effortless hose detachment for hassle-free maintenance.
- **Adhesive-Free Seal:** Facilitates easy installation and removal, enhancing convenience.
- **Dual Printer Compatibility:** Designed to work seamlessly with a second printer, the system includes the Combined Exhaust Ventilation System (CEVS) for integrating two printers into a single exhaust setup, effectively preventing backflow.
- **Better Cable Management:** By routing the CAN bus & PTFE cable out the exhaust port and the back of the machine, it provides a more aesthetically pleasing and clean look.
![](Reference_Images/Completed_Front_Example_Photo.jpg)
![](Reference_Images/Completed_Example_Photo.jpg)


# Installation Guide
  - Please follow the detailed steps in the [Installation Guide](Installation_Guide.md) to set up your V-Flow System.


## Prerequisites for V-Flow System Installation
To successfully set up the V-Flow system, the following components are essential:
- **Noctua NF-A6x25 Fan**: This fan is recommended ([Fume Extraction Analysis](Noctua-NF-A6x25-Fume_Extraction_Analysis.md)) for its efficient airflow and quiet operation. [View on Amazon](https://www.amazon.com/dp/B01K4HRLRI?psc=1&ref=ppx_yo2ov_dt_b_product_details)
- **Dryer Vent Window Kit**: This kit is designed for a 4-inch hose. However, the `Window_Vent_Hose_Adapter.stl`, found in the`Combined_Exhaust_Vent_System` STL folder, modifies this setup to accommodate a 2.5-inch hose. [View on Amazon](https://www.amazon.com/gp/product/B0BXWH53M4/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1).
- **2.5-inch Hose**: This hose connects the printer(s) to the window dryer vent. Note: The hose is available in 10ft lengths; assess your space to determine the required length for your setup. [View on Amazon](https://www.amazon.com/gp/product/B0C85G8P2R/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1).
- **Silicon Mats**: These mats are necessary for crafting one-way valves used with the CEVS. Additionally, adding a valve on the `Window_Vent_Hose_Adapter.stl` for single or dual printer setups can prevent backdraft, though it remains optional. [View on Amazon](https://www.amazon.com/gp/product/B083TKTJS5/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1).


## Recommended Mods
To enhance the performance of the V-Flow system and ensure optimal chamber temperature management, the following modifications are highly recommended:
- **Ellis Bed Fan Mod**: Essential for controlling chamber temperatures. This mod is crucial when using the V-Flow exhaust system. [Ellis Bed Fans Mod](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Bed_Fans).
- **Clicky-Clack Fridge Door Mod**: A highly recommended addition for its superior sealing properties, plus it's just an awesome mod. [Clicky-Clack Door Mod](https://github.com/tanaes/whopping_Voron_mods/tree/main/clickyclacky_door).
- **RockNRoll Mod**: Facilitates easier access to the electronics compartment by allowing the printer to be rolled onto its back without damaging cables or the exhaust system. [RockNRoll Mod](https://mods.vorondesign.com/detail/tiIhFDTh9tHJY0JNJK9A).
- **ACM Panels**: For enhanced thermal management and durability, using Aluminum Composite Material (ACM) panels for the bottom and back of the enclosure is recommended.
- **Extrusion End Caps**: My creation, `Extrusion_End_Cap.stl`, available in `STL_FILES/Accessories_&_Tools`, seals the gaps at the extrusion joints on the top of the machine.
- **Z-Covers & Z-Plug**: Remixed parts, originals sourced from the internet. These parts seal gaps around the Z motors, specific to Voron 2.4. Available in the `STL_FILES/Accessories_&_Tools` folder.
- **Bed Wiring Grommet by LoCoCNC**: Organizes and protects bed wires, offering a cleaner setup and better seal. [Bed Wiring Grommet](https://mods.vorondesign.com/detail/PNilw0WXR7Qmhquj749iFg).


## Contributions
  - If you have improvements or bug fixes, please submit a pull request or open an issue.


## License
  - This project is licensed under the [GNU General Public License v3.0](LICENSE).


# Acknowledgements
- The `Voron-Rear_Mounting_Plate.stl` is a remixed component. The `Voron-M16_Cable_Gland_Housing.stl` stl remains unchanged. Both are from the umbilical passthrough mod by [whopping_Voron_mods](https://github.com/tanaes/whopping_Voron_mods/tree/main/umbilical_passthrough)
- Inspiration for the one-way valve feature comes from the 2.4 Window Ventilation System available on [TeamFDM](https://www.teamfdm.com/files/file/463-24-window-ventilation-system/).
- The quick connect mechanism was inspired by The Aluminum Carpenter's [YouTube video](https://www.youtube.com/watch?v=LfHVOZGakTQ).

