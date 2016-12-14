.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Operation
=================================================

.. contents:: Table of Contents



Navigate to the Web Controller

-----------
Setting the Z offset
-----------

Here we will calibrate Robo C2 by setting the Z-Offset and making sure your first layer is applied correctly

From the home screen select "Utilities"
Then select "Wizards"
Next select "Z-Offset Wizard"
Your printer will now home itself and get in position to set your offset
Follow the directions on the screen by taking a piece of paper or something similar that is the same thickness as a piece of paper
Press on the 'Up' arrow to raise the bed up toward the nozzle of the printer
Slide the piece of paper in between the nozzle and bed and continue pressing the 'Up" button until you feel resistance on the paper between the Nozzle and the print bed. Note: You still want to be able to slide the piece of paper back and forth but with enough resistance that it is touching both the bed and the nozzle
Select 'Finished" 
Your printer will calculate your Z-Offset and then press 'Finished' to complete setting your Z-Offset

-----------
Start a print
-----------
   Slice with Slicer
   Upload Gcode, STL
   
Print Status
-----------
The status of your print is reflected in the web app under state.

Print Complete
-----------
You should receive a notification in an email or on the app when you print has completed.

Using print bed adhesion
-----------
The C2 does not require any additional adhesion.  If for some reason your print is not sticking to the bed, you may need to adjust your Z offset from the touch screen.

Removing the print
------------
When the Print is completed, remove the print plate with the finished print on it from the C2 by lifting the bed up and away from the magnets. 
Slowly slide the print bed out of the machine and hold with two hands on opposite ends of the print plate. 
Now, flex the print plate back and forth to create a gap in between the print and the print plate. Move to the opposite corners and repeat twisting until the majority of the print has come loose.
Carefully remove the print from the print plate with your hand.
Note: if the print is not coming loose after flexing the bed, use the provided spatula scraper carefully to skim the border of your print. Slowly work your way underneath the print toward the middle until your print comes loose. Do not try and pull the print from the plate directly up from the middle, as it may cause your print to break.

Hotend Removal
-------------
If you need to remove the hotend due to a clog or changing the nozzle.  You can do so by loosening the hex head screw on the extruder mount above.  Once you loosen it, the cowl ( or clamp ) inside the extruder will release and the hotend should drop down.  The wires for the heating element and thermistor are plugged into the extruder as well, you can take those out and make note of where you unplugged them from.

