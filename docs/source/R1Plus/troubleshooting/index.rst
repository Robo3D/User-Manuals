.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Troubleshooting
=================================================

.. image:: images/r1-blank.jpg
   :alt: R1 Header
   :align: center

---------------
Print Not Sticking to Bed
---------------

If you are experiencing problems with the plastic not adhering to your print bed, there are a few things that can be done;

Clean the build plate
---------------

After some time, the build plate adhesion can become unsticky and plastic will no longer be able to stick to it. Resurface this by grabbing some isopropyl alcohol and giving it a good wipe down. Afterwards re-applying the provided glue stick or other adhesion type. .

Using a raft
---------------

Make sure to use a raft on all of your parts when preparing your print. This will allow a bigger surface area of plastic to stick to the bed, and can compensate for a small amount of unlevel bed.

Lower fan speed
---------------

If your prints are still curling after the above solutions are attempted, you can try lowering your fan speed to stop the plastic from cooling too fast and shrinking, causing warping. To do this go into your desktop software. Under the settings> speed> fan speed and turn this setting down to 30%.

First Layer Height and Width
---------------

Set your first layer height to 0.3mm. This will allow more plastic to flow out of your nozzle, allowing a better adhesion to your print bed. You can also try making your first layer width of plastic higher. Usually a first layer width of 1mm is optimal - this will extrude more plastic at a lower layer height to allow more surface area of plastic bind to the print bed.

Printing with ABS plastic
---------------

ABS plastic is much more temperamental as far as cooling goes than other types of plastic. This is where you will see the most warping issues. Try not to use the print cooling fan for this material. You can set this to be turned off in an ABS preset.

---------------
Nozzle Clogging
---------------

From time to time, your hot end may become clogged or jammed. This can happen for a number of reasons.

1. Not using the correct temperature settings. If the temp on the extruder is not high enough for the type of plastic you are using, the plastic will have problems passing through the hot end, which will cause a clog.

2. Attempting to use PLA in an extruder that still has ABS in it. When you switch from a high temp plastic like ABS to something that extrudes at a lower temperature, it is very important to clear the nozzle of any remaining plastic to prevent clogging. Before your next print, manually heat the hot end to ABS temps and push a little bit of PLA through it. Once all of the ABS is cleared you can take the temp back down to the suggested PLA temp and should have no problem extruding.

---------------
Extrusion - Filament Grinding
---------------

Extrusion doesn’t just depend on heat. There are a few other factors that can keep your extruder from working:

Tangled Filament
---------------

If the filament on your spool for some reason becomes tangled or knotted up, it will eventually create tension and the extruder will not have enough power to pull it through.

Filament Latch too Loose
---------------

If there is not enough pressure on the hobbed bolt teeth from the filament latch.

Clogged Hot End Tip
---------------

This happens when there is something stuck in the bottom of the hot end, preventing the filament from being pushed any further.

---------------
Stringing Prints
---------------

Stringing is caused primarily by a lack of retraction.

Retraction is important because it helps to eliminate the inherent oozing of plastic out of the hotend tip. When the hot end is full of plastic and stops extruding after a layer of a print to move to a new position, there is a bit of filament the will ooze if it is not pulled back out of the hot end. This will attach to the surface of the print and then be dragged across the print, creating an ugly string across the entire part.

You can set retraction in your Slicer Settings under “Extruder”.

Temperature is another factor that plays into stringing. If your temps are too hot for the plastic type that you are using, this may cause more stringing
