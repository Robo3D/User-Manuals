.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Troubleshooting
=================================================

.. image:: Images/troubleshooting.png
   :alt: Getting Started
   :align: center

Print Not Sticking to Bed
---------------

If you are experiencing problems with the plastic not adhering to your print bed, there are a few things that can be done;

1. **Update**
  * Make sure to update your printer to the latest version of RoboOS. This will ensure that you have the latest version of the firmware that is flashed to your controller board, and have the most up-to-date and tested version of build plate leveling.
2. **Re-run the z-offset wizard**
  * Re-running the z-offset wizard will make sure that your bed is properly leveled. To do this, on the menu screen go to Utilities> Wizards>Z-offset Wizard.
3. **Replace the build plate adhesion**
  * After some time, the build plate adhesion can become un-sticky and plastic will no longer be able to stick to it. Replace this with the black tape that came with your printer or order more from our store at www.robo3d.com. Unpeel the used build tape from the build plate, and replace with a new, fresh piece. Remember to re-calibrate your offset by selecting the z-offset wizard from the utilities menu.

.. image:: Images/Applying-bed-tape.gif
   :alt: Applying Bed Tape
   :align: center

4. **Using a raft**
  * Make sure to use a raft on all of your parts when preparing your print. This will allow a bigger surface area of plastic to stick to the bed, and can compensate for a small amount of an unleveled bed.

5. **Lower fan speed**
  * If your prints are still curling after the above solutions are attempted, you can try lowering your fan speed to stop the plastic from cooling too fast and shrinking, causing warping. To do this go into your desktop software Cura for Robo. Under the settings> speed> fan speed and turn this setting down to 30%.

Grinding Noise when Starting a Print
---------------

If you are experiencing a grinding noise when trying to start a print, or when your printer is homing, there are some things to take a look at to make sure your printer hardware is in the right place. Sometimes during shipping or traveling, some things can come loose, so lets check those.

1. **Rods are out of place**
 * Make sure your rods are in the correct position. While moving to the home position, these rods will hit switches to let the printer know it is in the 0 position. If these rods have been moved out of the way, they will not hit the switch, and the printer will try and continue to travel past its 0 position, resulting in a grinding noise. The picture below will show you how they will look out of place, and also how they should look to work correctly.

.. image:: Images/rod-out.png
   :alt: Rod Out
   :align: center

.. image:: Images/rod-in.png
   :alt: Rod In
   :align: center

* To correct these, hold the plastic bracket the end of the rod is being held by with one hand. With your other hand, grab the rod that is furthest to the back left of the printer and slowly slide it into place (left on the x axis, away from you (back) on the y axis).

.. image:: Images/adjusting-rod.gif
   :alt: Adjusting Rod
   :align: center

* Note: Make sure that the rod is not directly touching the side wall of the printer when placing back into its position. Once you have slid the rod over to the edge of the wall, back it off just slightly so it is not rubbing the side wall when moving back and forth.

Material Not Extruding
---------------

1. **Nozzle isn't heating up**
 * Make sure all of your wiring is plugged in and firmly mounted in its correct brackets.
 * Nozzle Wires should be plugged into the correct terminals on the underside of the extruder.

.. image:: Images/Fanelectonicsplugs.png
   :alt: Fan Electronics
   :align: center

* Wires should be plugged in and seated correctly on the top electronics board at the top of the extruder. Remove the extruder cover then check the wires.

.. image:: Images/Extruder-cover-off.gif
   :alt: Extruder Cover Off
   :align: center

.. image:: Images/Extruderelectronicstop.png
   :alt: Extruder Electronics
   :align: center

2. **Drive Gear is not cleaned**
 * Turn Off the Printer
 * Take off the extruder cover
 * Use a toothbrush to clean this drive gear of debris shown in the picture
 * Turn the shaft, and continue scrubbing until it is cleaned of debris

.. image:: Images/Drive-gearscrub.png
   :alt: Drive Gear Clean
   :align: center


3. **Material is stuck around the spool**
  * Every so often, the material can get stuck on the spool holder or in the spool itself
  * If the material is tangled on the spool holder, unwind about 12 inches or 25 cm of filament to loosen it, then reel it back around the spool neatly, trying not to cross over plastic as it spools onto itself
  * If the material is tangled within the spool, you will need to unwind some the spool and see where it is crossing over itself. Cut the plastic where you find it is crossing over itself, and feed it back into the machine.

4. **Drive Gear is not tightened down**
 * If your motor shaft is turning, but the drive gear is not, it means you need to tighten down your drive gear.
 * To do this, turn off your machine and remove the extruder cover.

.. image:: Images/Extruder-cover-off.gif
   :alt: Extruder Cover Off
   :align: center

* Next, unscrew the extruder tensioner cover with a screwdriver.

.. image:: Images/Tensionercover.png
   :alt: Remove Tensioner Cover
   :align: center

* Take the allen wrench that came in your tool kit, and unscrew the bolt connecting the extruder tensioner to the extruder.

.. image:: Images/Tensionerscrew.png
   :alt: Remove Tensioner Screw
   :align: center

* Once that is off, go ahead and use the smaller allen wrench to screw the drive gear set screw tight. Make sure it is seated all the way up to the spacer.

.. image:: Images/Drive-gear-tightening.png
   :alt: Extruder Cover Off
   :align: center

* Now reverse these steps to put it all back together

Shifting Layers/bad print quality
---------------

1. **Loose Pulleys**
 * If the pulleys on the X and Y axis come loose, you may need to tighten down the set screws to hold these in place.
 * Move the Extruder into the center of the printer, and find the set screws on the pulleys in the corners of the axis. There are a total of 10 pulleys that you must check (2-3 in each corner), and each has 2 set screws to make sure to tighten down.

.. image:: Images/Pulley-tightening.png
   :alt: Extruder Cover Off
   :align: center

2. **Unaligned Axis**
  * Re-align your axis to be perpendicular to each other. To do this, use the orange clips that came with your printer.
  * Unplug your machine, and move your extruder to the front right corner.
  * Using the orange rod stabilizers, attach one at each corner of the gantry, completing a square. This should re-align your brackets and revive your print quality.

Hotend Clogged
---------------

1. **Not Heating up enough**
 * Make sure all of your wiring is plugged in and firmly mounted in its correct brackets.
 * Nozzle Wires should be plugged into the correct terminals on the underside of the extruder.
 * Wires should be plugged in and seated correctly on the top electronics board at the top of the extruder.

.. image:: Images/Fanelectonicsplugs.png
   :alt: Fan Electronics
   :align: center

.. image:: Images/Extruderelectronicstop.png
   :alt: Extruder Electronics
   :align: center

2. **Material stuck below the Drive Gear**
 * If your motor shaft is turning, but the drive gear is not, it means you need to tighten down your drive gear.
 * To do this, turn off your machine and remove the extruder cover.

.. image:: Images/Extruder-cover-off.gif
   :alt: Extruder Cover Off
   :align: center

* Next, unscrew the extruder tensioner cover with a screwdriver.

.. image:: Images/Tensionercover.png
   :alt: Remove Tensioner Cover
   :align: center

* Take the allen wrench that came in your tool kit, and unscrew the bolt connecting the extruder tensioner to the extruder.

.. image:: Images/Tensionerscrew.png
   :alt: Remove Tensioner Screw
   :align: center

* Once that is off, go ahead and use the smaller allen wrench to unscrew the drive gear set screw loose.

.. image:: Images/Drive-gear-tightening.png
   :alt: Extruder Cover Off
   :align: center

* From here, you can use the tweezers that came in your tool box to grab onto the filament that is stuck. Be sure to heat up the hotend before trying to pull out the filament.

3. **Hotend fan is not on**
  * If your hotend fan is not on (the third fan on the back of the extruder), then it is most likely your hotend isn't being cooled enough and will jam your nozzle. The fan is most likely unplugged.
  * Take the red and black fan wires, and look for the terminal plug that is empty on the back underside of the extruder.

.. image:: Images/Fanelectonicsplugs.png
   :alt: Fan Electronics Plugs
   :align: center

Hotend Falling Out
---------------

If you are experiencing your hotend falling out from the extruder, there is a simple fix that will lock your extruder in place

1. **The tension screw is not tight enough**
 * The allen screw located on the front aluminum plate is the tensioner that holds your hotend in place. It is likely that this has come loose. Grab the allen wrench out of the the tool kit that came with your printer.
 * Make sure to turn off your printer.
 * Loosen your hotend by turning the tensioner screw counterclockwise a few turns.

.. image:: Images/Hotend-tensioner-loosen.gif
   :alt: Loosening Hotend
   :align: center

* Push the hotend as far as it can go up into the seated ring and make sure it is flat against it.
* While you are holding it there, screw the allen screw clockwise until you feel a good amount of resistance and the hotend cannot be pulled out with your hand. Make sure you align the heater block to be parallel with the front of the extruder so the hotend cover will lay flat against the magnets when reinstalling.

.. image:: Images/Tightening-hotend-tensioner.gif
   :alt: Tightening Hotend
   :align: center

* Turn the printer back on and test. If it still falls out, try tightening the allen screw even more.

Screens Goes White or Doesn't Work
---------------

If the screen is not working there is a few steps that need to be taken to solve the issue.

1. **Loose Wiring**
 * First, remove the black bezel (which is the black plastic holding the screen) by gently pulling inward from the inside edge of the plastic. From here you will be able to see the electronics of the printer.

.. image:: Images/Bezel-removal.gif
   :alt: Bezel Removal
   :align: center

* Next, raise your bed by manually turning the long threaded z screw until the bed is mostly all the way up. Now remove the internal lid under the bed that says Robo on it for better access to the electronics.

.. image:: Images/Z-Screw-Raise.gif
   :alt: Raising Z Screw
   :align: center

.. image:: Images/Inside-Cover-Removal-2.gif
   :alt: Inside Cover Removal
   :align: center

* Here, you will see a ribbon cable attached that attaches the screen to a green electronics board. On the screen side, detach the screen cable and re-attach. Do the same thing for the green electronics board side.

.. image:: Images/Screen-Plug-2.gif
   :alt: Screen Plug
   :align: center

.. image:: Images/Pi-Ribbon-Cable-2.gif
   :alt: Pi Screen Plug
   :align: center

* Next, find the micro usb cord that is plugged into the bottom right corner of the green electronics board. Unplug this and plug it back in.

.. image:: Images/Pi-Power-Cable.gif
   :alt: Pi Power
   :align: center

* Finally, follow the micro usb cord you just unplugged and follow it to the other end on the black board. It should be plugged in on the black electronics board in a terminal labeled 5V right next to Fan2 plug in. Unplug and re-plug this back in.

.. image:: Images/Pi-Power-Black.png
   :alt: Pi Power black
   :align: center

2. **If your screen is still broken**
  * Contact customer support at www.robo3d.com/support

Hotend Cover is falling off
---------------

If your hotend cover is falling off when printing, or is teetering side to side and not flat against the extruder, more that likely your hotend is blocking it. To fix this, follow these steps:

1. Remove your hotend cover.

2. Loosen the hotend tensioner screw slightly. You do not need to loosen it completely, only enough to be able to rotate the hotend while it is still indie its mount.

.. image:: Images/Hotend-tensioner-loosen.gif
   :alt: Loosening Hotend
   :align: center

3. Align the heater block to be parallel with the extruder carriage. Make sure the heater block is not turned in such a way that it is sticking out past the extruder carriage.

.. image:: Images/hotend-alignment.png
   :alt: alignment
   :align: center

4. Tighten the hotend tensioner screw. Remember to not overtighten this screw, as it may be hard to perform maintenance later.

5. Replace the hotend cover

Filament Runout Sensor Error
---------------

If you see an error while printing that detects your filament has run out, there are a few options to get this working, or bypass it.

1. **Make sure you are not bypassing the filament block**

* In order for the filament sensor to work correctly, the filament needs to be run through the filament block on the backside of your printer. The filament sensor is located in this black block and will give an error of no filament if the filament is being run on the outside. Make sure you run all filament through this block to ensure the filament sensor will detect your material.

2. **Disable the filament runout sensor**

* If the filament runout sensor is still reading that there is no filament inside your printer, even though it is going through the filament sensor block, you can disable this software setting via the web browser. Take these steps to disable the filament sensor:

1. Connect your printer to wifi. Go to Utilities> Network> Configure wifi and connect your printer.

2. Once you are successfully connected to the internet, lets find your IP address. Go to Utilities> Network> Network Status. Here you will find the IP address.

3. Next, open up your browser (such as Google Chrome, or Mozilla Firefox), and enter that same IP address into the address bar. You should see a dashboard come up that looks like this:

.. image:: Images/6.png
   :alt: Octoprint Dashboard
   :align: center

4. Click on the 'Settings' button in the top right of the interface.

5. A settings window will pop up. On the left hand side, scroll down and select the item labeled 'Plugin Manager' under 'Octoprint' about half way down the list.

6. You will now see a list of plugins that are installed onto your printer. From here click the next page over until you see the line item labeled 'Filament Sensor'. Click on the small black button to the right of the item (circled in green in the picture below).

.. image:: Images/plugin-manager.PNG
   :alt: Octoprint Plugin Manager
   :align: center

7. Once you have de-selected this plugin, you will need to restart octoprint. A pop up will show on the top right of the interface - click 'restart now'. You should be good to print without filament runout detection interruption.

.. image:: Images/restart-now.PNG
   :alt: Octoprint Restart Now
   :align: center
