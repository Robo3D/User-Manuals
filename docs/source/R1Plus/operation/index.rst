.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Operation
=================================================

.. image:: images/r1-blank.jpg
   :alt: R1 Header
   :align: center

-----------
Controls
-----------

The “CONTROLS” tab is where you can physically control your printer through the software. Here you can pre heat your extruder and heated bed, and even adjust your print speed while printing.

Adjusting Temperatures
-----------

To adjust your temperature for either the extruder or heated bed, simple type your desired temps in the “target” field. You can also use the 'preheat' button to heat up these things while you set your slice settings.

To set up your preheat buttons click the button next to either “Extruder Temperature Override” or “Bed Temperature Override”. You will see a screen like this appear, and can now enter in the desired preheat temp settings.

**An Extruder Preheat should not be set to be higher than 240 for ABS filament or 210 for PLA filament**

**A Bed Preheat should not be set to higher than 90 for ABS and 55 for PLA filament**

Once you have set up your preheat buttons, save them and they will show in your Controls panel.

Movement Controls
-----------

You can use the movement controls on this panel (while your printer is idle) to move the X, Y and Z axis. The extrude/retract motor movement keys help in loading filament as well. You can unlock the motors after a print job in order to move them around by hand if need be. Also, if you need to home any or all of your axis you can do it here.

Speed Control
-----------

If for some reason you need to adjust the speed at which your unit is printing, use the “tuning adjustment” speed multiplier slider at the bottom of the screen. Drag it left to slow and right to speed up printing. (This will only work while printing)

-----------
Robo R1+ Plus 3D Print Workflow
-----------

In this section we will be walking through the 3d printing workflow for your Robo R1+ Plus.

Uploading file to MatterControl
-----------

1. Open up MatterControl and connect to your printer.
2. Within the 'Queue', select the 'Add' button on the bottom left corner.
3. Add your file to the queue.
4. When it shows up in the queue, select the file that you uploaded by clicking on it.
5. When it is selected it will show up in the preview panel.

Pre Heat
-----------

Now is a great time to preheat your extruder and heated bed because they take a couple of minutes to get up to temp. Do this in your Controls panel by clicking on the preheat buttons. Click the button that corresponds to the type of plastic you will be printing with.

Set Slice Setting
-----------

After preheating your extruder and heated bed, now make sure that you have your Slice settings exactly the way that you want them. Select your Quality and Material presets from the dropdown menus in the 'Slice Settings' tab on the left hand window.

If you need to make any last minute changes to a particular slice setting you can also do it now. Once you have made your change, you will see a “Save” button appear above the material preset. Make sure to click SAVE before continuing.

Check the build plate
-----------

One last thing to double check before your start your pint is your build plate. Make sure that your part is oriented the way you like. To check this, click the preview window at the top of your screen.

If you made any changes to the orientation of your part, make sure to save them before starting your print.

Prepare the build plate
-----------

In order for the plastic to stick to the glass of the build plate, you must use an adhesive. You can use a couple of different techniques for prepping your buildplate. The three that we most commonly use here at Robo are:

1. Vinyl Sheeting
2. Glue Stick (supplied with your tool kit)
3. Hairspray (AquaNet works very well)

Move the heated bed all the way out to the furthest forward it can go and raise the x axis out of the way (using the motor controls in your Control Panel).

Apply your adhesive and make sure that there are no bumps on the build plate.

Run
-----------

Now just click the start button! You will notice that your part slices in the software right before the print starts and the printer runs and auto leveling measurement sequence. From here let the printer do the rest of the work and watch your part grow!

-----------
Loading Filament
-----------

To begin loading filament, click on the 'pre-heat' button within MatterControl to begin heating up your nozzle.

While that is heating up, hang your filament spool on the spool holder. Be sure to unroll at least 11”— or 30 centimeters — of filament and cut the tip with a pair of scissors. Thread it through the top of the filament passing hole at the top of your printer and into the extruder. You may need to pull back the filament thumb latch in order to create and opening and feed it all the way down.

.. image:: images/insert-filament-R1+ Plus.gif*********
   :alt: Unhinge Spool Holder
   :align: center

You may spin the filament drive gear by hand to push the filament down, into the nozzle, and out the other end. Once you see this, your filament is successfully loaded.

.. image:: images/fil-load-3-R1+ Plus.gif**********
   :alt: Filament In Extruder
   :align: center


---------------
Removing the print
---------------

When the print is complete and cooled down, use the provided spatula to carefully remove the print at its borders. Then, slowly work your way underneath the print until it’s loose. Don’t force the print loose by pulling it up directly up from the print bed, since this may cause your print to break.

.. image:: images/removing-print-R1+ Plus.gif*********
   :alt: Removing Print
   :align: center

-----------
Setting your Z-Offset
-----------

If the offset on your printer is somehow not calibrated correctly, it may be too low or too high. Z-offset measures the distance between “On” and “Off” in your Z endstops for auto leveling. There is sometimes a tolerance to this because of the way that the endstop parts are manufactured. R1+ Plus 3D printers come standard with a Z offset of 0.9

To adjust your z offset you only need to press one of the macro buttons within MatterControl. Pressing the Macro button will save the offset to that value and you will not need to press it again unless you want to change your z offset to a different value.

* Lower z offsets are 0.8 and 0.9.
* Higher z offsets are 1, 1.1 and 1.2.
