# "Nova" - An Ender 5 Plus Clone, designed from scratch
This is my attempt at cloning the Creality Ender 5 Plus printer. This printer will have the following specs:
- Build volume: 310mm x 310mm x 350mm
- TMC2209 step motor drivers for quiet operation
- 0.9 degree NEMA17 stepper motors for greater accuracy
- Direct Drive assembly - No more bowden tubes! Should help printing TPU without any issues
- SKR 1.4 Turbo control board
- TFT35 Touch Screen display
- External MOSFET components to power the hotend and the heated bed (to protect the components on the SKR board which are only rated for 10A)
- NO sensorless homing: Limit switches will be used as they are more reliable

The **Bill of Materials** can be found here:
https://docs.google.com/spreadsheets/d/1B5keSqVwSLgc5OjsFatlqAnYNtMWsLssTLB85XMptbM/edit?usp=sharing

I will document the build process shortly and add to this page.

## To-do List
- [X] Model the design in Sketchup
- [X] Export and print the individual components (STL format)
- [X] Create a bill of materials based on the design
- [X] Clone and configure the marlin firmware for the board
- [X] Design the "control box" to house all the electronics below the print bed
- [ ] Create drag chains for cable management (keeping in mind: We want the hotend to be "hot swappable" so have components use connectors)
- [X] Tap and drill holes in the aluminum pieces as required
- [X] Assemble the frame of the printer
- [X] Install mechanical components (Stepper motors, belts, etc...)
- [X] Test the electronic components:
  - [X] Control board 
  - [X] TFT Display
  - [X] Power Supply
  - [ ] Stepper Motors
    - [X] Z-Steppers
    - [X] Y-Stepper
    - [X] X-Stepper
  - [X] External MOSFETs
  - [X] Heated Bed
  - [X] Hotend Assembly

![image](https://user-images.githubusercontent.com/17118188/113151056-b76e9680-9202-11eb-80e0-381878f2ae20.png)
