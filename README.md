# "Nova"
Nova is an Ender 5 Plus inspired 3D printer. While I "borrowed" some ideas of the movements, I designed the entire printer using Sketchup.

![image](https://user-images.githubusercontent.com/17118188/117857136-74b8c900-b25a-11eb-9464-94b7c1c22436.png)

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
- ALWAYS make sure you test your ABL probe on a breadboard or any other way without connecting it to your printer. I had made a mistake with my initial voltage divider and measured 8V from the probe. Had this been installed, I would've fried my SKR!
- The power supply I ordered only has two DC outputs, so I chose to use one output for only the heated bed and the other for the hotend heater and the mainboard.
- The MOSFET modules are absolutely essential when using an SKR board. These boards have integrated MOSFETs for the heated bed and hotend, but they're rated at 10A max. With my bed at 240W and using 24V, that would put me right at the maximum current rating. I'd rather replace a $15 module than a $85 board!

## Still to do
There are a few things I have yet to fix:
- [ ] I need to install some drag chains so the "umbilical cord" stops dragging against the steel rods and to look somewhat better.
- [ ] Design a new electronics enclosure to move the box hanging from the side to the bottom, similar to the Ender 5 setup.
- [ ] Due to how the movements work, I can add Foamboard to the back, left and front with minimal effort to make an enclosure, but I'll still need to create a hood / roof for the X/Y axes.
