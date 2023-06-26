# SNES Repro Cart

## Description
This is a SNES repro cart project to be used with original hardware. This project makes extensive use of the work already completed by MouseBiteLabs and is more of an educational project for myself.
- [MouseBiteLabs GitHub](https://github.com/MouseBiteLabs),
- [MouseBiteLabs website](https://mousebitelabs.com/).  

My project also includes a 'multifunction' cart using a single board for both HiROM and LoROM that can be swapped via dip switches instead of two separate board designs.

## Status
The `.json` files can be opened in [EasyEDA Designer](https://easyeda.com/editor).
### HiROM 6264 SRAM
This is a HiROM PCB using a 6264 SRAM chip.
This design makes some use of SMT (surface mount technology) components.
 - **Completed**

### HiROM 62256 SRAM
This is a HiROM PCB using a 62256 SRAM chip.
This design makes **no use** of SMT components and is easier to solder if you are doing it yourself.
 - **PCB completed**
 - Schematics in progress

Both HiROM carts are virtually identical and have to do with what type of SRAM you have available or can procure. They will function virtually identically.

### LoROM
- In progress

### Multifunction
This cart makes use of dip switches and pull-down resistors to combine a LoROM and HiROM cart in one. The HiROM to LoROM swap can be done via dip switches.  
- Component placement completed
- Traces routing in progress

## Author
Jérôme Launay