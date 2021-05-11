# Assembly

For the assembly we'll break it into six sections.

## Frame Base

To assemble the base of the frame:

- Arrange four 2020 extrusions in a square with the front and back between the left and right sides. You will end up with a build that is 540mm wide.
- Attach the four sides together using four printed LowerAngleBracket.stl and two M3x10mm bolts and M3 TNuts per corner.
- Attach the four 2040 extrusions to each corner (two tapped holes facing down AND the one tapped hole facing the inside) using 2 x M5x45mm bolts. Note that the wide sides should face towards the front of the printer.

## Upper Frame
- Arrange four 2020 extrusions in a square with the front and back between the left and right sides.
- Attach the four sides to each-other using the four UpperAngleBracket.stl two M3x10mm bolts and M3 TNuts per corner.
- Temporarily attach the upper frame to the rest of the frame using two M5x45mm bolts through the front and back sections into the tapped upright holes.
- Attach the YMotorBracket.stl to the center of the back section of the upper frame using two M3x10mm bolts and M3 TNuts.
- Attach your dual-shaft stepper motor to the bracket.

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

## Build Platform
- Using the remaining two 500mm 2020 extrusions and the two 400mm extrusions, place the shorter ones down and place the longer ones on top at a distance equal to the mounting holes of the bed.
- Attach everything using M5 bolts and install your bed using the recess screws and bed levelling nuts.
- Attach the two LeadScrewNutHolder.stl to the sides using TNuts. Try to get them exactly in the center, but don't worry too much at this stage, you will likely adjust them later in the build process.
- Install three POM wheels on each of the four ZAxisPlate.stl, taking care to install the single wheel (under the "bump") using an eccentric nut.
- On each end of the sides of extrusion that are "sticking out", attach your assembled ZAxisPlate.stl using M5 bolts and nuts.
- Remove the top frame again and slide the entire bed frame over the corners.
- Once the Z axis is sliding on the corners, attach the top frame back onto the bottom frame temporarily. (Note that this might not be super easy, depending on how accurately you drilled the holes)

## Z Motors and Lead Screws
- Attach a stepper motor to both of the ZMotorBracket.stl
- Attach the stepper motor and bracket assembly to the center of each side on the bottom of the frame. Don't worry about getting this exactly in the center, you will likely have to adjust once the build is more complete.
- Install a coupler on each motor.
- Slide the lead screws through the top of the lead screw nut holder, through the anti-backlash nuts into the coupler. 
- Now move your build platform up and down to it's maximums to adjust everything to the center without tilting. Take your time here to make sure you get it right. I had to redo this a number of times as the build platform kept "tilting" after moving the Z axis down and up again.

## Y Axis
- Remove the top frame from the printer again.
- Insert a 608 bearing into each of the two YAxisCover.stl and set aside for now.
- Place a 5mm to 8mm coupler on each shaft coming out of the Y motor.
- Add a steel shaft to the other side of each coupler and add an 8mm toothed pulley to the other end of each shaft. (Try not to allow them to bend too far as this may cause damage to the couplers)
- With the shaft and pulley installed, attach the Y axis cover using a single M3x10mm bolt and TNut in the top-most hole and add the second M3x10 bolt and T-Nut in the lower hole without attaching it anywhere. Note that the shaft should run parallel to the top-back corner of the frame.
- Once you've installed the covers, install the belts in a similar fashion as you did for the X axis: Hold a tensioner in place against one of the front ends and measure out a belt and attach the belt to the respective gantry plate. Do this on both sides.
- Attach the entire X and Y axis assemblies to the rest of the printer frame using 4 x M5x45mm bolts.
- Complete the attaching of the YAxisCover.stl bottom screw into the side of the 2040 extrusion from the uprights.

Congratulations, you have completed the build! Up next is the Electronics.