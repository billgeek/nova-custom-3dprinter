# Build Instructions

There are three main categories to the build instructions, each with a set of steps to complete.

## Drilling and Tapping

Find the drilling and tapping instructions here: https://github.com/billgeek/nova-custom-3dprinter/blob/main/DRILLING_AND_TAPPING.md

## Lower Frame Assembly

## Upper Frame Assembly

## X Axis

## Build Platform

## Z Motors

## Y Axis

## Electronics


Assemble the frame base:
	- Arrange four 2020 extrusions in a square with the front and back between the left and right sides. You will end up with a build that is 540mm wide.
	- Attach the four sides together using the lower angle brackets and two M3x10mm bolts and M3 TNuts per corner.
	- Attach the 2040 extrusion to each corner using 2 x M5x45mm bolts, taking care to have the hole with the tapped thread facing the inside of the printer. Note that the 40mm sides should face forward.

Assemble the upper frame:
	- Arrange four 2020 extrusions in a square with the front and back between the left and right sides.
	- Attach the four sides together using the upper angle brackets and two M3x10mm bolts and M3 TNuts per corner.
	- Temporarily attach the upper frame to the rest of the frame using two M5x45mm bolts.
	- Attach the Y stepper bracket to the center of the back section of the upper frame using two M3x10mm bolts and M3 TNuts.
	- Attach your Y stepper motor to the Y stepper bracket.

Assemble the X axis:
	- Using the 600mm 2020 extrusion, attach it to the X motor bracket and X axis gantry plate using 4 x M5x45mm bolts and nyloc nuts.
	- Attach the X motor to the motor bracket.
	- Add a toothed pulley to the X Motor.
	- Add the gantry plate to the extrusion bar. (You may have to either do this before attaching the X axis plate or remove a POM wheel to "clip" it on.
	- Assemble a smooth pulley into one of the tensioner assemblies and unscrew the tensioner until you have the shortest possible distance. (IE: Allow yourself to pull the belt later)
	- Holding the tensioner in place against the end of the X Axis, measure out a belt and attach the belt to the entire assembly.
	- Attach four POM wheels to either side of the axis using two eccentric nuts per plate.
	- Remove the top frame from the lower frame and slide the x axis over the sides. You may need to remove the "front" bar of the top frame to achieve this.
	- Once the X axis is sliding on the top frame, attach the top frame back onto the bottom frame temporarily.

Assemble the build plate frame:
	- Using the remaining two 500mm 2020 extrusions and the two 400mm extrusions, place the shorter ones down and place the longer ones on top at a distance equal to the mounting holes of the bed.
	- Attach everything using M5 bolts and install your bed using the recess screws and bed levelling nuts.
	- Attach the lead screw nut holders to the sides using TNuts. Try to get them exactly in the center.
	- On each end, attach a Z axis plate with the three POM wheels. (Remember to include an eccentric nut for the inner POM wheel!)
	- Remove the top frame again and slide the entire bed frame over the corners.
	- Once the Z axis is sliding on the corners, attach the top frame back onto the bottom frame temporarily.

Attach Z motors:
	- Attach a stepper motor to each of the Z motor brackets.
	- Attach the stepper motor and bracket to the center of each side on the bottom of the frame.
	- Install a coupler on each motor.
	- Slide the lead screws through the top of the lead screw nut holder, through the anti-backlash nuts into the coupler. This is where adjustments will have to be made to ensure the bed can move from the top to the bottom freely without the lead screw tilting.

Complete Y axis: This is probably the most tricky part...

	- Remove the top frame from the printer again.
	- Insert a 608 bearing into each of the two Y axis covers and set aside for now.
	- Place a 5mm:8mm coupler on each shaft coming out of the Y motor.
	- Add the steel shaft to the other side of the coupler and add an 8mm toothed pulley to the other end of the shaft. (Try not to allow them to bend too far as this may cause damage to the couplers)
	- With the shaft and pulley installed, attach the Y axis cover using a single M3x10mm bolt and TNut in the top-most hole and add the second M3x10 bolt and T-Nut in the lower hole without attaching it anywhere. Note that the shaft should run parallel to the top-back corner of the frame.
	- Once you've installed the covers, install the belts in a similar fashion as you did for the X axis: Hold a tensioner in place against one of the front ends and measure out a belt and attach the belt to the respective gantry plate. Do this on both sides.
	- Attach the entire X and Y axis assemblies to the rest of the printer frame using 4 x M5x45mm bolts.


Electronics:
