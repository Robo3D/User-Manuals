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

.. image:: images/r1-blank.jpg*******
   :alt: Image of Control Tab
   :align: center

Adjusting Temperatures
-----------

To adjust your temperature for either the extruder or heated bed, simply type your desired temps in the "Target” field. The two "PREHEAT" buttons will heat the extruder to 210 and the bed to 50 respectively, by default.

.. image:: images/r1-blank.jpg*******
   :alt: Image with pencil highlighted and the popup screen
   :align: center


You can set up to three of your own PREHEAT presets by clicking on the pencil icon next to "Extruder Temperature". This will trigger a popup where you can label each preset and enter your desired temperature. The same can be done for the Bed Temperature.


.. image:: images/r1-blank.jpg*******
   :alt: Image highlighting label and temperature
   :align: center

.. note:: An Extruder Preheat should be set between 230-250 for ABS filament or 190-210 for PLA filament. A Bed Preheat should be set between 80-100 for ABS and 50-70 for PLA filament

Once you have set up your preheat buttons, save them. They will show up next to the PREHEAT button.

Movement Controls
-----------

You can use the movement controls on this panel (while your printer is idle) to move the X, Y and Z axis. The extrude/retract motor movement keys help in loading and unloading filament as well. You can unlock the motors after a print job in order to move them around by hand if need be. Also, if you need to home any or all of your axes you can do it here.

Speed and Extrusion Control
-----------

If you need to adjust the speed at which your extruder is printing, under Tuning Adjustment us the  "Speed Multiplier" slider at the bottom of the screen. If you want to adjust the rate at which your printer is extruding filament use the "Extrusion Multiplying". Drag it left to slow it down and right to increase the speed or flow rate. (This will only work while printing)


-----------
Uploading file to MatterControl
-----------

1. Open up MatterControl and connect to your printer.
2. Within the 'Queue', select the 'Add' button on the bottom left corner.
3. Add your file to the queue.
4. When it shows up in the queue, select the file that you uploaded by clicking on it.
5. When it is selected it will show up in the preview panel.

-----------
Setting your Z-Offset
-----------

If the offset on your printer is somehow not calibrated correctly, it may be too low or too high. Z-offset measures the distance between “On” and “Off” in your Z endstops for auto leveling. There is sometimes a tolerance to this because of the way that the endstop parts are manufactured. R1+ Plus 3D printers come standard with a Z offset of 0.9

To adjust your z offset you only need to press one of the macro buttons within MatterControl. Pressing the Macro button will save the offset to that value and you will not need to press it again unless you want to change your z offset to a different value.

* Lower z offsets are 0.8 and 0.9.
* Higher z offsets are 1, 1.1 and 1.2.

-----------
Pre Heat
-----------

Now is a great time to preheat your extruder and heated bed because they take a couple of minutes to get up to the desired temperature. Do this in your Controls panel by clicking on the preheat buttons. Click the button that corresponds to the type of plastic you will be printing with.



Set Slice Settings
-----------

After preheating your extruder and heated bed, double check that your slice settings are correct. Select your Quality and Material presets from the dropdown menus in the 'Settings' tab on the left hand window. In the frame below, can switch between Basic, Standard, and Advanced slicing settings that will allow you to make a range of fine adjustments to how your print will be sliced.

**You can also add presets  you will see a “Save” button appear above the material preset. Make sure to click SAVE before continuing.*******

-----------
Load Filament
-----------

While that is heating up, hang your filament spool on the spool holder. Be sure to unroll at least 11”— or 30 centimeters — of filament and cut the tip with a pair of scissors. Thread it through the top of the filament passing hole at the top of your printer. Once your extruder is heated, insert the filament into the extruder. You may need to pull back the filament thumb latch in order to create an opening to feed the filament into the feeder gear.

.. image:: images/insert-filament-R1+ Plus.gif*********
   :alt: Unhinge Spool Holder
   :align: center

You may spin the filament drive gear by hand to push the filament down, into the nozzle, and out the other end. Once you see this, your filament is successfully loaded.

.. image:: images/fil-load-3-R1+ Plus.gif**********
   :alt: Filament In Extruder
   :align: center

-----------
Check the build plate
-----------

Make sure that your part is oriented efficiently. To check this, click the preview window at the top of your screen.

If you made any changes to the orientation of your part, make sure to save them before starting your print.

-----------
Print Bed Adhesives
-----------

In order for the plastic to stick to the glass of the build plate, you must use an adhesive. You can use a couple of different techniques for prepping your build plate. The three that we most commonly use here at Robo are:

1. Vinyl Sheeting
2. Glue Stick (supplied with your tool kit)
3. Hairspray (AquaNet works very well)

Move the heated bed all the way out to the furthest forward it can go and raise the x axis out of the way (using the motor controls in your Control Panel).

Apply your adhesive and make sure that there are no bumps on the build plate.

Run
-----------

Now just click the start button! You will notice that your part slices in the software right before the print starts and the printer runs an auto leveling measurement sequence. From here let the printer do the rest of the work and watch your part grow!


-----------
Removing the print
---------------

When the print is complete and cooled down, use the provided spatula to carefully remove the print at its borders. Then, slowly work your way underneath the print until it’s loose. Don’t force the print loose by pulling it up directly up from the print bed, since this may cause your print to break.

.. image:: images/removing-print-R1+ Plus.gif*********
   :alt: Removing Print
   :align: center
