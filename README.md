# "Nova"
Nova is an Ender 5 Plus inspired 3D printer. While I "borrowed" some ideas of the movements, I designed the entire printer using Sketchup.

## Specifications
- Build volume: 310mm x 310mm x 350mm
- TMC2209 step motor drivers
- 0.9 degree NEMA17 stepper motors (X and Y axes)
- Direct Drive assembly 
- SKR 1.4 Turbo mainboard
- TFT35 Touch Screen display
- External MOSFET components to power the hotend and the heated bed
- Sensorless homing

## Bill of Materials
See the below Google Sheet for the bill of materials:

https://docs.google.com/spreadsheets/d/1B5keSqVwSLgc5OjsFatlqAnYNtMWsLssTLB85XMptbM/edit?usp=sharing

## Build Process
Under construction - I will update the Build process once completed.

## Printed Parts
Under construction - There are a handful of STL files and Sketchup designs in this repository, but they've been updated and are scattered all over my PC. I need to go through all of the parts and update the files as needed.

## Firmware
I used the 2.0.x branch of Marlin when building the firmware for the printer. The configuration files are stored here in this repository.

## Gallery
I've uploaded a few pics to Google Photos during and after the build:

https://photos.app.goo.gl/cp9zkkoZYTewc5xc9

## Lessons Learned
This project taught me a lot of how printers and electronics work in general. Below are some takeaways I think are worth mentioning:
- Not all proximity sensors are made equal! The PL08-N sensors I received operate slightly differently than the standard "round" sensors and as such, I have the light permanently on due to disabling pull-up resistors.
- Squareness of the frame is critical. If your frame is not square, you will guaranteed not have decent quality. Use a T-square or something similar to ensure your build is perfectly square.
- On the SKR1.4, instead of using one driver for both Z motors, I decided to use E1 (second extruder) to drive the second Z motor. This is actually super easy to do, take a look at the included config.
- Instead of setting firmware to invert some axes, I decided to swap pins instead. Inverting in firmware works, but I didn't want to reflash yet again.

![image](https://user-images.githubusercontent.com/17118188/117857136-74b8c900-b25a-11eb-9464-94b7c1c22436.png)
