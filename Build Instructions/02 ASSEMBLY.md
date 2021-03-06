# Assembly

For the assembly we'll break it into six sections.

## Frame Base

To assemble the base of the frame:

- Arrange four 2020 extrusions in a square with the front and back between the left and right sides. You will end up with a build that is 540mm wide.
- Attach the four sides together using four printed LowerAngleBracket.stl and two M3x10mm bolts and M3 TNuts per corner.
- Attach the four 2040 extrusions to each corner (two tapped holes facing down AND the one tapped hole facing the inside) using 2 x M5x45mm bolts. Note that the wide sides should face towards the front of the printer.

![image](https://user-images.githubusercontent.com/17118188/117889395-7a75d500-b281-11eb-8e85-120e904511a1.png)

![image](https://user-images.githubusercontent.com/17118188/117889406-7cd82f00-b281-11eb-804e-7fb7094124b3.png)


## Upper Frame
- Arrange four 2020 extrusions in a square with the front and back between the left and right sides.
- Attach the four sides to each-other using the four UpperAngleBracket.stl two M3x10mm bolts and M3 TNuts per corner.
- Temporarily attach the upper frame to the rest of the frame using two M5x45mm bolts through the front and back sections into the tapped upright holes.
- Attach the YMotorBracket.stl to the center of the back section of the upper frame using two M3x10mm bolts and M3 TNuts.
- Attach your dual-shaft stepper motor to the bracket.

![image](https://user-images.githubusercontent.com/17118188/117889426-89f51e00-b281-11eb-8049-0c57b63aee54.png)

![image](https://user-images.githubusercontent.com/17118188/117889437-8eb9d200-b281-11eb-8744-d4bd6d172489.png)

![image](https://user-images.githubusercontent.com/17118188/117889469-97120d00-b281-11eb-9d73-8eb5f5228868.png)

![image](https://user-images.githubusercontent.com/17118188/117889478-9b3e2a80-b281-11eb-9614-6ece47aa8fde.png)

## X Axis
- Using the 600mm 2020 extrusion, attach it to the XMotorBracket.stl and XAxisGantryPlate.stl using 4 x M5x45mm bolts and nyloc nuts.
- Attach the stepper motor for the X movement to the motor bracket.
-  Add a toothed pulley to the X Motor.
- Add the hotend gantry plate to the extrusion bar. (You may have to either do this before attaching the X axis plate or remove a POM wheel to "clip" it on)
- Add a smooth pulley into one of the tensioner assemblies and unscrew the tensioner until you have the shortest possible distance. (IE: Allow yourself to pull the belt later)
- Holding the tensioner in place against the end of the X Axis, measure out a belt and attach the belt to the entire assembly.
- Attach four POM wheels to either side of the axis using two eccentric nuts per plate.
- Remove the top frame from the lower frame and slide the X axis over the sides. You may need to remove the "front" bar of the top frame to achieve this.
- Once the X axis is sliding on the top frame, attach the top frame back onto the bottom frame temporarily.

![image](https://user-images.githubusercontent.com/17118188/117889501-a85b1980-b281-11eb-9423-01c52ccf23a6.png)

![image](https://user-images.githubusercontent.com/17118188/117889533-b5780880-b281-11eb-9891-749c87b2af60.png)

## Build Platform
- Using the remaining two 500mm 2020 extrusions and the two 400mm extrusions, place the shorter ones down and place the longer ones on top at a distance equal to the mounting holes of the bed.
- Attach all the extrusions together using M5 bolts. Do not install your bed yet as there's still work to do and you probably don't want to damage it.
- Attach the two LeadScrewNutHolder.stl to the sides using TNuts. Try to get them exactly in the center, but don't worry too much at this stage, you will likely adjust them later in the build process.
- Install three POM wheels on each of the four ZAxisPlate.stl, taking care to install the single wheel (under the "bump") using an eccentric nut.
- On each end of the sides of extrusion that are "sticking out", attach your assembled ZAxisPlate.stl using M5 bolts and nuts.
- Remove the top frame again and slide the entire bed frame over the corners.
- Once the Z axis is sliding on the corners, attach the top frame back onto the bottom frame temporarily. (Note that this might not be super easy, depending on how accurately you drilled the holes)

![image](https://user-images.githubusercontent.com/17118188/117889544-bc068000-b281-11eb-94e9-b651382e55f8.png)

![image](https://user-images.githubusercontent.com/17118188/117889556-c32d8e00-b281-11eb-9fb8-4d8eb7bb30c3.png)

## Z Motors and Lead Screws
- Attach a stepper motor to both of the ZMotorBracket.stl
- Attach the stepper motor and bracket assembly to the center of each side on the bottom of the frame. Don't worry about getting this exactly in the center, you will likely have to adjust once the build is more complete.
- Install a coupler on each motor.
- Slide the lead screws through the top of the lead screw nut holder, through the anti-backlash nuts into the coupler. 
- Now move your build platform up and down to it's maximums to adjust everything to the center without tilting. Take your time here to make sure you get it right. I had to redo this a number of times as the build platform kept "tilting" after moving the Z axis down and up again.

![image](https://user-images.githubusercontent.com/17118188/117889670-f243ff80-b281-11eb-82ef-15fa2b6539f1.png)

## Y Axis
- Remove the top frame from the printer again.
- Insert a 608 bearing into each of the two YAxisCover.stl and set aside for now.
- Place a 5mm to 8mm coupler on each shaft coming out of the Y motor.
- Add a steel shaft to the other side of each coupler and add an 8mm toothed pulley to the other end of each shaft. (Try not to allow them to bend too far as this may cause damage to the couplers)
- With the shaft and pulley installed, attach the Y axis cover using a single M3x10mm bolt and TNut in the top-most hole and add the second M3x10 bolt and T-Nut in the lower hole without attaching it anywhere. Note that the shaft should run parallel to the top-back corner of the frame.
- Once you've installed the covers, install the belts in a similar fashion as you did for the X axis: Hold a tensioner in place against one of the front ends and measure out a belt and attach the belt to the respective gantry plate. Do this on both sides.
- Attach the entire X and Y axis assemblies to the rest of the printer frame using 4 x M5x45mm bolts.
- Complete the attaching of the YAxisCover.stl bottom screw into the side of the 2040 extrusion from the uprights.

## Final Touches
- Install your heated bed to the build platform using the tapered M4 screws, springs and levelling knobs of your choice. (You can either purchase some or find some available on Thingiverse)

Congratulations, you have completed the build! Up next is the Electronics.
