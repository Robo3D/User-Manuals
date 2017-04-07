.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Robo Web Dashboard
=================================================

Here we will explain what dashboard is and what features it has. Also put a link to the dashboard quick start guide

There will be a graphic explaining what octoprint does and call out features:

Upload files (both stl and gcode)
Slice files with onboard slicing
Start and stop a print
View layers of the model from a selected gcode
move motors
preheat nozzle and build plate
on board camera
Set timelapse from the on board cameras
manage plugins
Update software
z offset
view terminal of commands
View history of printer
View statistics of printer
monitor
  temperature
  print time left
  gcode commands

Overview
---------------
Here is a picture of the interface with call outs to where stuff is.

(insert picture of interface here)

How to connect
---------------

There are three different ways to connect to the web dashboard from your browser:

Note: Make sure your Robo C2 or Robo R2 is connected to the wireless network or in hotspot mode or else you wont be able to connect to your printer in the web browser.

**IP Address**

1. Here we can use the IP address of your printer to login to the web dashboard. On the screen of the Robo C2 or Robo R2, go to Utilities> Network> Network Status. Here you will see an IP address. Copy this IP address down and bring it over to your computer.

2. Open up your web browser (such as Google Chrome or Mozilla Firefox), and enter this IP address into the address bar. If you entered it correctly, you will see a web dashboard come up.

.. image:: images/ip-name.PNG
   :alt: IP Name
   :align: center

Note: You can also connect via a web browser on a smartphone for on-the-go connectivity

**Printer name via Bonjour**

1. Mac and iOS Users
 * First, locate the printer name. There are three places this is shown; On the back of the printer, on the screen under Utilities> Network> Network Status, and on the bar code sticker that came on original box
 * With this name known, go to your web browser and type the name into the web browser address bar followed by a .local/  (examples below).
 * Example - Printer Name: **plastic-gordon**, you would enter **plastic-gordon.local/** into your web browser address bar.
 * Example - Printer Name: **compassionate-shirley**, you would enter **compassionate-shirley.local/** into your web browser address bar.

.. image:: images/bonjour-name.PNG
   :alt: Bonjour Name
   :align: center

2. Windows and others

 * In order to use bonjour to connect to your printer on a browser via it's name, you will need to install the bonjour extension in order for your computer to recognize names as IP address'. Download here
 * Once installed follow the steps used for Mac and iOS users above.

**Hotspot Mode**

1. To use hotspot mode, select hotspot mode on your printer via Utilities> Network> Start WiFi Hotspot
2. Now look for your IP address under Utilities> Network> Network Status
3. Next, go to your computer and make sure to connect to the printers wifi hotspot.
4. Now, type the IP address into your web browsers web address bar and the dashboard should pop up.

Uploading stl Files
---------------


Explain here how to upload stl files (and what happens to slice)

Uploading gcode Files
---------------

If you have already sliced your file via Cura for Robo, or another slicer program, there are two main ways to upload gcode files to your printer. By the 'Upload' button, as well as a 'drag-and-drop' approach.

1. The 'Upload' Button is located where the file list is towards the bottom of the list.

.. image:: images/upload-file-button.PNG
   :alt: Upload File Button
   :align: center

2. You can also simply drag your gcode file from your computer into the dashboard. The dashboard will get dark, and you may then drop the file onto the left side of the dashboard where it says 'upload'

.. image:: images/upload-file-drag.PNG
   :alt: Upload File
   :align: center

Set temperature and move motors
---------------
1. Under the 'Temperature' section of the web dashboard, you can set temperatures for your nozzle and your bed (Robo R2 only). This is a good place to toggle your temperatures if your material needs more or less heat.

.. image:: images/temp-control.PNG
   :alt: Upload File
   :align: center

2. Under the 'Control' section of the interface, you can move your motors and extrude filament. Use the arrows and the distance to move ijn the desired location. Remember to heat up your nozzle before using the 'extrude' and 'retract' buttons.

.. image:: images/controls.PNG
   :alt: Upload File
   :align: center

View on-board camera + timelapse (Robo R2 only)
---------------

1. Viewing your print with the camera

2. Timelapse feature


Manage plugins
---------------

Which plugins do what

Update software
---------------

How to update your software

View history and statistics of printer
---------------

(pic of Interface showing what is what)

Set your z-offset
---------------

EEprom settings go here

Monitor your print
---------------

Start, pause and cancel your print explanations
