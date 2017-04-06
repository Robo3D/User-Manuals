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

There are two different ways to connect to the web dashboard from your browser:

Note: Make sure your Robo C2 or Robo R2 is connected to the wireless network or else you wont be able to connect to your printer in the web browser.

**IP Address**

1. Here we can use the IP address of your printer to login to the web dashboard. On the screen of the Robo C2 or Robo R2, go to Utilities> Network> Network Status. Here you will see an IP address. Copy this IP address down and bring it over to your computer.

2. Open up your web browser (such as Google Chrome or Mozilla Firefox), and enter this IP address into the address bar. If you entered it correctly, you will see a web dashboard come up.

**Printer name via Bonjour**

1. Mac and iOS Users
 * First, locate the printer name. There are three places this is shown; On the back of the printer, on the screen under Utilities> Network> Network Status, and on the bar code sticker that came on original box
 * With this name known, go to your web browser and type the name into the web browser address bar followed by a .local/  (examples below).
 * Example - Printer Name: **plastic-gordon**, you would enter **plastic-gordon.local/** into your web browser address bar
2. Windows and others

 * In order to use bonjour to connect to your printer on a browser via it's name, you will need to install the bonjour extension in order for your computer to recognize names as IP address'. Download here
 * Once installed follow the steps used for Mac and iOS users above.

Here we will explain how to connect (both via ip address and via bonjour)

Uploading Files
---------------

Explain here how to upload stl files (and what happens to slice)

Explain here how to upload gcode files

Set temperature and move motors
---------------

Explain here how to set temperatures

Explain here how to move motors (remember temp needs to be up to move extruder)

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

Interface showing what is what

Set your z-offset
---------------

EEprom settings go here

Monitor your print
---------------

Start, pause and cancel your print explanations
