.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Troubleshooting
=================================================

.. image:: Images/r2-troubleshooting.jpg
   :alt: Getting Started
   :align: center

---------------
Print Not Sticking to Bed
---------------

If you are experiencing problems with the plastic not adhering to your print bed, there are a few things that can be done;

1. **Update**
  * Make sure to update your printer to the latest version of RoboOS. This will ensure that you have the latest version of the firmware that is flashed to your controller board, and have the most up-to-date and tested version of build plate leveling.

2. **Re-run the z-offset wizard**
  * Re-running the z-offset wizard will make sure that your bed is properly leveled. To do this, on the menu screen go to Utilities> Wizards>Z-offset Wizard.

  **Use the fine tune offset wizard**

  * If you are experiencing the nozzle dragging (too low) or your prints are not sticking (too high), you can fine-tune your Z-Offset.  It's a little more work, but you will tune your offset by actually printing on the bed to get the perfect height. Your Robo R2 will print a series of vertical lines, one at a time.  Between each pass you can increase or decrease the Z-Offset value as needed. To use the fine-tune offset wizard, follow these steps below:

  * Note: It is very important to make sure that the print bed is level by adjusting the thumb screws below the print bed before starting this wizard.

To start, select 'Utilities' from the home screen, then select 'Fine tune offset'. Select the material currently loaded in the printer. Then the wizard will ask you which corner you'd like to start from. This simply sets where the printer will start printing out the test lines. You can start from whichever corner you prefer.

.. image:: Images/fine-tune-1.gif
    :alt: Fine tune 1
    :align: center

Once the printer homes and positions itself to begin testing, you will see a visual reference on the screen to help you know what to look for in order to find an ideal Z-Offset value.

.. image:: Images/fine-tune-2.gif
    :alt: Fine tune 2
    :align: center

You will come to the "Adjust Offset" screen, where you can set the adjustment increment, move the bed up or down, and test the offset. We recommend testing the offset first so you can get a visual reference to fine tune the current offset. Move the bed up and down with the provided buttons on screen, and test with the 'test offset' button to see if it looks satisfactory.

.. image:: Images/fine-tune-3.gif
    :alt: Fine tune 3
    :align: center

When you've found a satisfactory Z-Offset value, press the forward arrow in the top right corner and select 'Save' to finish the wizard.

.. image:: Images/fine-tune-4.gif
    :alt: Fine tune 4
    :align: center

3. **Clean and repurpose the build plate adhesion**
  * After some time, the build plate adhesion can become unsticky and plastic will no longer be able to stick to it. Resurface this by grabbing some 2000 grit sand paper and lightly sanding the surface, afterwards cleaning it with a damp cloth. Remember to re-calibrate your offset by selecting the z-offset wizard from the utilities menu.

4. **Using a raft**
  * Make sure to use a raft on all of your parts when preparing your print. This will allow a bigger surface area of plastic to stick to the bed, and can compensate for a small amount of unlevel bed.

5. **Lower fan speed**
  * If your prints are still curling after the above solutions are attempted, you can try lowering your fan speed to stop the plastic from cooling too fast and shrinking, causing warping. To do this go into your desktop software Cura for Robo. Under the settings> speed> fan speed and turn this setting down to 30%.

6. **First Layer Height and Width**
  * Set your first layer height to 0.3mm. This will allow more plastic to flow out of your nozzle, allowing a better adhesion to your print bed. You can also try making your first layer width of plastic higher. Usually a first layer width of 1mm is optimal - this will extrude more plastic at a lower layer height to allow more surface area of plastic bind to the print bed.

---------------
Grinding Noise when Starting a Print
---------------

If you are experiencing a grinding noise when trying to start a print, or when your printer is homing, there are some things to take a look at to make sure your printer hardware is in the right place. Sometimes during shipping or traveling, some things can come loose, so lets check those.

1. **Rods are out of place**
 * Make sure your rods are in the correct position. While moving to the home position, these rods will hit switches to let the printer know it is in the 0 position. If these rods have been moved out of the way, they will not hit the switch, and the printer will try and continue to travel past its 0 position, resulting in a grinding noise. The picture below will show you how they will look out of place, and also how they should look to work correctly. (note: images below are for the Robo C2 but will act the same way for the Robo R2)

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

---------------
Material Not Extruding
---------------

1. **Nozzle isn't heating up**
 * Make sure all of your wiring is plugged in and firmly mounted in its correct brackets.
 * Nozzle Wires should be plugged into the correct terminals on the underside of the extruder.

.. image:: Images/Fanelectonicsplugs.png
   :alt: Fan Electronics
   :align: center

* Wires should be plugged in and seated correctly on the top electronics board at the top of the extruder. Remove the extruder cover then check the wires.

.. image:: Images/extruder-cover-off-r2.gif
   :alt: Extruder Cover Off
   :align: center

.. image:: Images/Extruderelectronicstop.png
   :alt: Extruder Electronics
   :align: center

2. **Drive Gear is not cleaned**
 * Turn Off the Printer
 * Take off the extruder cover

.. image:: Images/extruder-cover-off-r2.gif
   :alt: Extruder Cover Off
   :align: center

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

.. image:: Images/extruder-cover-off-r2.gif
   :alt: Extruder Cover Off
   :align: center

 * Next, unscrew the extruder tensioner cover with a screwdriver.
 * Take the allen wrench that came in your tool kit, and unscrew the bolt connecting the extruder tensioner to the extruder.
 * Once that is off, go ahead and use the smaller allen wrench to screw the drive gear set screw tight. Make sure it is seated all the way up to the spacer.

.. image:: Images/Drive-gear-tightening.png
   :alt: Drive gear tightening
   :align: center

* Now reverse these steps to put it all back together

---------------
Shifting Layers/bad print quality
---------------

1. **Loose Pulleys**
 * If the pulleys on the X and Y axis come loose, you may need to tighten down the set screws to hold these in place.
 * Move the Extruder into the center of the printer, and find the set screws on the pulleys in the corners of the axis. There are a total of 10 pulleys that you must check (2-3 in each corner), and each has 2 set screws to make sure to tighten down.

2. **Unaligned Axis**
  * Re-align your axis to be perpendicular to each other. To do this, use the orange clips that came with your printer.
  * Unplug your machine, and move your extruder to the front right corner.
  * Using the orange rod stabilizers, attach one at each corner of the gantry, completing a square. This should re-align your brackets and revive your print quality.

---------------
Hotend Clogged
---------------

1. **Not Heating up enough**
 * Make sure all of your wiring is plugged in and firmly mounted in its correct brackets.
 * Nozzle Wires should be plugged into the correct terminals on the underside of the extruder.
 * Wires should be plugged in and seated correctly on the top electronics board at the top of the extruder.

.. image:: Images/Fanelectonicsplugs.png
   :alt: Fan Electronics
   :align: center

.. image:: Images/uptowncables.png
   :alt: Extruder Electronics
   :align: center

2. **Material stuck below the Drive Gear**
 * If your motor shaft is turning, but the drive gear is not, it means you need to tighten down your drive gear.
 * To do this, turn off your machine and remove the extruder cover.

.. image:: Images/extruder-cover-off-r2.gif
   :alt: Extruder Cover Off
   :align: center

 * Next, unscrew the extruder tensioner cover with a screwdriver.
 * Take the allen wrench that came in your tool kit, and unscrew the bolt connecting the extruder tensioner to the extruder.
 * Once that is off, go ahead and use the smaller allen wrench to unscrew the drive gear set screw loose.

.. image:: Images/Drive-gear-tightening.png
   :alt: Drive gear tightening
   :align: center

* From here, you can use the tweezers that came in your tool box to grab onto the filament that is stuck. Be sure to heat up the hotend before trying to pull out the filament.

3. **Hotend fan is not on**
  * If your hotend fan is not on (the third fan on the back of the extruder), then it is most likely your hotend isn't being cooled enough and will jam your nozzle. The fan is most likely unplugged.
  * Take the red and black fan wires, and look for the terminal plug that is empty on the back underside of the extruder.

.. image:: Images/Fanelectonicsplugs.png
   :alt: Fan Electronics Plugs
   :align: center

---------------
Hotend Falling Out
---------------

If you are experiencing your hotend falling out from the extruder, there is a simple fix that will lock your extruder in place

1. **The tension screw is not tight enough**
 * The allen screw located on the front aluminum plate is the tensioner that holds your hotend in place. It is likely that this has come loose. Grab the allen wrench out of the the tool kit that came with your printer.
 * Make sure to turn off your printer.
 * Loosen your hotend by turning the tensioner screw counterclockwise a few turns.
 * Push the hotend as far as it can go up into the seated ring and make sure it is flat against it.
 * While you are holding it there, screw the allen screw clockwise until you feel a good amount of resistance and the hotend cannot be pulled out with your hand. Make sure you align the heater block to be parallel with the front of the extruder so the hotend cover will lay flat against the magnets when reinstalling.
 * Turn the printer back on and test. If it still falls out, try tightening the allen screw even more.

---------------
Screens Goes unresponsive or Doesn't Work
---------------

If the screen is not working there is a few steps that need to be taken to solve the issue.

1. **Loose Wiring**
* First, raise your bed by manually turning the long threaded z screw until the bed is mostly all the way up. Now remove the internal lid under the bed that says Robo on it for better access to the electronics.
* Here, you will see an HDMI cord that attaches the screen to a green electronics board. On the green electronics board side, detach the HDMI cable and re-attach.
* Next, you will see a ribbon cable plugged into the green electronics board that will need to be unplugged, and re-plugged back in.
* Next, find the micro usb cord that is plugged into the bottom right corner of the green electronics board. Unplug this and plug it back in.
* Finally, follow the micro usb cord you just unplugged and follow it to the other end on the black board. It should be plugged in on the black electronics board in a terminal labeled 5V right next to Fan2 plug in. Unplug and re-plug this back in.

.. image:: Images/Pi-Power-Black.png
   :alt: Pi Power black
   :align: center

2. **If your screen is still broken**
  * Contact customer support at www.robo3d.com/support

---------------
Hotend Cover is falling off
---------------

If your hotend cover is falling off when printing, or is teetering side to side and not flat against the extruder, more that likely your hotend is blocking it. To fix this, follow these steps:

1. Remove your hotend cover.

2. Loosen the hotend tensioner screw slightly. You do not need to loosen it completely, only enough to be able to rotate the hotend while it is still inside its mount.

3. Align the heater block to be parallel with the extruder carriage. Make sure the heater block is not turned in such a way that it is sticking out past the extruder carriage.

4. Tighten the hotend tensioner screw. Remember to not overtighten this screw, as it may be hard to perform maintenance later.

5. Replace the hotend cover

---------------
Drive Gear aligning and tightening
---------------

If your drive gear has come loose and/or it is not aligned with the filament to hotend pathway, take these steps to realign and retighten:

Note: Make sure there is no filament loaded into the extruder. If there is, heat up your extruder and remove any filament.

1. Remove your extruder cover.

.. image:: Images/extruder-cover-off-r2.gif
   :alt: Extruder Cover Off
   :align: center

2. Turn the extruder motor shaft so that the flat surface of the shaft is pointing at 10 o'clock (see picture below).

.. image:: Images/10oclock.png
   :alt: 10 oclock
   :align: center

3. Use your allen wrench to loosen the set screw on the drive gear so that it is able to freely spin on the motor shaft.

.. image:: Images/loosen-drive-gear.png
   :alt: loosen drive gear
   :align: center

4. Now we are going to align and tighten your drive gear. Grab a small length of filament to help you through this.

5. Apply pressure to the filament lever arm and insert the filament through the filament feed hole.

6. Push and pull the filament, while making sure it is centered with the drive gears grooves, until the drive gear is in position (it will self align when the filament starts passing through it).

.. image:: Images/drive-gear-alignment-r2.gif
   :alt: Gear Alignment
   :align: center

7. Align the set screw with the flat surface of the motor shaft. Visually check to make sure the groove on the drive gear is aligned with the hole going down to the hotend.

8. Tighten the set screw on the flat surface of the motor shaft.

.. image:: Images/tighten-drive-gear.png
   :alt: loosen drive gear
   :align: center

9. Replace your extruder cover and you are all set.

---------------
Filament Runout Sensor Error
---------------

If you see an error while printing that

1. **Make sure you are not bypassing the filament block**

* In order for the filament sensor to work correctly, the filament needs to be run through the filament block on the backside of your printer. The filament sensor is located in this black block and will give an error of no filament if the filament is being run on the outside. Make sure you run all filament through this block to ensure the filament sensor will detect your material.

2. **Disable the filament runout sensor**

* If the filament runout sensor is still reading that there is no filament inside your printer, even though it is going through the filament sensor block, you can disable this software setting via the web browser. Take these steps to disable the filament sensor:

1. Connect your printer to Wi-Fi. Go to Utilities> Network> Configure Wi-Fi and connect your printer.

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

7. Once you have de-selected this plugin, you will need to restart Octoprint. A pop up will show on the top right of the interface - click 'restart now'. You should be good to print without filament runout detection interruption.

.. image:: Images/restart-now.PNG
   :alt: Octoprint Restart Now
   :align: center

---------------
Firmware Update
---------------

This will walk you through the steps to update your firmware from the touchscreen and a USB drive.

1. Make sure you have the latest firmware. Download here: R2_Firmware_.

.. _R2_Firmware: https://robo3d.com/wp-content/uploads/2017/06/Marlin.R2.1.1.7.hex_.zip

2. Unzip the file and place the file onto a USB drive.
3. Place the USB drive into the USB slot on the front of your Robo R2.
4. On the touchscreen, navigate to Utilities > Options > Firmware Update

.. image:: Images/options-screen.png
   :alt: Options Screen
   :align: center

5. The next screen will show the .hex firmware file from your USB drive that you put on in step 2.

.. image:: Images/firmware-screen.png
   :alt: Firmware Select
   :align: center

6. Click on the file name, and click 'Start' to start your firmware update.

.. image:: Images/confirm-hex-file.png
   :alt: Confirm Hex File
   :align: center

7. Wait a few minutes for the firmware to be loaded onto your Robo R2, and it will automatically reconnect.

.. image:: Images/firmware-is-updating.png
   :alt: Firmware is Updating
   :align: center

8. Your Robo R2 should now have the latest firmware updated.

---------------
Checking your Pogo Pins
---------------


If you notice that your bed seems to be heating up too slowly or your print bed is not being recognized check your pogo pins.

To do so, start by removing the heated bed.

.. image:: Images/remove-bed.gif
   :alt: Remove Bed.
   :align: center

Then check the 6 golden colored pins. Press down on each one, they should all be rebound when pressed down and have a spring like feel.

.. image:: Images/check.gif
   :alt: Check Pins
   :align: center

If one of the pins is not rebounding back to its original position, you may need to replace your pogo pin pcb.

.. image:: Images/retract.jpg
   :alt: Retract pins
   :align: center





---------------
Print Bed Pogo Pin Connection Replacing
---------------

If your Robo R2 gives you an error of your print bed not being recognized, even though it is on the printer, and seated properly, you may have to replace your pogo pin connection electronics. Remember to never take off your print bed when it is hot or heating - this can cause the print bed electronics to break. Also, remember to make sure your print bed is flat by adjusting the screws underneath the bed so it is not teetering back and forth when you press onto the corners - this too can cause the print bed electronics to break. To replace the electronics board, follow these steps.

1. Make sure to turn off your printer, and then take your print bed out.

.. image:: Images/bed-out.gif
   :alt: Taking bed out
   :align: center

2. Look toward the back of the plate that the print bed seats into, you will see a small black electronics board with gold pins on it. This is the board we will be replacing. Go ahead and unscrew the 4 screws on the corners, then carefully unplug the wire from the socket. Keep your screws close for the next step.

.. image:: Images/pogo-pin-out.gif
   :alt: Pogo Pin out
   :align: center

3. Now that you have the board out, take the new board, and first, plug in the wire to the plug socket. Then, screw in the board to the print plate.

.. image:: Images/pogo-pin-in.gif
   :alt: Pogo Pin In
   :align: center

4. Now, place your print bed back into the printer. Make sure to tap on each corner to see if the bed is teetering. If it is, adjust the thumb screws under the print plate to get it nice and even. If the print bed is teetering, this can cause the pogo pins to not contact the heat bed correctly, and result in a failed electronics board.

.. image:: Images/bed-in.gif
   :alt: Bed In
   :align: center

5. You're all set to begin printing!

---------------
Z-Limit Switch Replacing
---------------

If your Robo R2 seems to be not homing correctly when the print bed moves all the way to the bottom of the printer, you may have a faulty z limit switch. In order to replace this switch, follow these steps:

1. Turn your printer on, and navigate to the motors controls from the main screen. In the top right corner, select to move the print bed to the top of the printer so you can have easier access to the z limit switch.

.. image:: Images/bed-up.gif
   :alt: Bed Travel Up
   :align: center

2. Next, remove the internal hatch to gain access to the internal parts.

.. image:: Images/hatch-out.gif
   :alt: Internal Hatch out
   :align: center

3. Now, in the back of the area you just uncovered, on the middle left, you will see the z axis limit switch. Take a screwdriver and remove the two screws shown below. Be sure to keep the screws where you can easily find them.

.. image:: Images/z-limit-screws.png
   :alt: Z Limit Screws
   :align: center

4. Once you have removed the screws, the limit switch will only be connected by a plug. Carefully unplug the limit switch from its wires.

.. image:: Images/z-limit-screws-out.png
   :alt: Z Limit Screws Out
   :align: center

.. image:: Images/z-limit-plug.png
   :alt: Z Limit Plug
   :align: center

5. Now, find your new z limit switch. It is easiest to start by inserting the screws into the switch before plugging in.

.. image:: Images/z-limit-in-1.png
   :alt: Z Limit Screws In
   :align: center

6. Plug the switch into the wires, and screw back in your limit switch to the proper placement. The screw holes are shown below, as they are a little hard to find.

.. image:: Images/z-limit-holes.png
   :alt: Z Limit Screws Holes
   :align: center

7. You're all set to begin printing!

---------------
Door Replacement
---------------

If you have received a replacement door for Robo R2, follow these quick few installation steps to have you back up and running in no time.

1. Remove the door you wish to replace. It is easiest to open the door all the way in order to access the hardware. There are 2 screws holding the door to its hinges, one screw per hinge. Carefully unscrew the door from each hinge, starting with the bottom hinge. Remember to keep the screws and magnets that are inside this door.

.. image:: Images/door-before.png
   :alt: Door Before Removal
   :align: center

.. image:: Images/door-unscrew-top.png
   :alt: Unscrewing top hinge
   :align: center

2. Take out the hardware - 2 magnets and a screw per hinge, and set it to the side.

.. image:: Images/door-hardware.png
   :alt: Door Hardware
   :align: center

3. Next, to make installation easiest, place the screw through the hole in the door, then place the square magnet on the other side. Now, place the rectangle magnet behind the square magnet.

.. image:: Images/door-place-screw.png
   :alt: Screw First
   :align: center

.. image:: Images/door-magnet-1-in.png
   :alt: Magnet 1
   :align: center

.. image:: Images/door-magnet-2-in.png
   :alt: Magnet 2
   :align: center

4. Next, place the new door onto the hinges, making sure the rectangle magnets seat all the way into the cavity, and the door sits flush. Then, start screwing the door into the hinges.

.. image:: Images/door-top-in.png
   :alt: start screwing door
   :align: center

5. Finally, push the door all the way into the hinges so they are seated all the way in and flush. Now, screw the two screws all the way into the hinges.

.. image:: Images/door-top-push.png
   :alt: Push door
   :align: center

.. image:: Images/door-top-in-2.png
   :alt: All the way
   :align: center

---------------
Error Messages
---------------

If you are receiving error messages on your Robo R2, the following instructions will give you information about them, and also show you how to fix them and get you back up and running in no time.

Connection Interrupted
---------------

This connection interrupted error is a result of the main electronics board not being detected. There are a few ways this can happen - more discussed below.

1. First step in resolving this error is trying to reset the connection to the printer. A button is displayed within the error message labeled 'Reset'. Press that to initiate an electronics reset. If this doesn't work, look to the next step to try and resolve the problem.

2. Check your wiring on the top of your extruder. Make sure the two ribbon cables on the top of extruder are locked into place. Also, make sure the other white plugs are seated into their sockets all the way.

.. image:: Images/Extruderelectronicstop.png
   :alt: Extruder Electronics
   :align: center

3. Check the wiring on your hotend. Sometimes these can come loose and send an error to the electronics. There will be two sets of wires. One for the temperature reading, and one for the heating power. Make sure these plugs are seated all the way up into their sockets. The wires should be seated all the way to the left. The thinner wires are the ones that go toward the front of the extruder, and the thicker, all red wires should be plugged into the plug towards the back of the extruder.

.. image:: Images/hotend-wires.jpg
   :alt: Hotend Electronics
   :align: center

4. Check the wiring on your main electronics board. Every so often, the ribbon cable coming from the main electronics board can come loose. You will need to first take the inner panel out, located inside the printer below the bed, to get to the inside of the printer. Once that is out, you will see two electronics boards. We want to look at the one on the left, which is black. On the back right of the black electronics board, there is a ribbon cable plugged in. Make sure this ribbon cable is seated all the way down into its plug to ensure there is a proper connection.

.. image:: Images/hatch-out.gif
   :alt: Internal Hatch out
   :align: center

.. image:: Images/electronics-ribbon.jpg
   :alt: Electronics ribbon
   :align: center
