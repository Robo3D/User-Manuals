.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Firmware
=================================================

.. image:: images/r1-blank.jpg
   :alt: R1 Header
   :align: center

Periodically check for Firmware updates to ensure you're making the most out of your Robo!

Here you will find a guide to help you easily update your firmware with arduino.

------------
Download the Files
------------
Make sure you use the correct firmware specific for your printer.

**R1 +:**

.. _R1+_firmware: http://download.robo3d.com/firmware/R1Plus/ROBO3DR1PLUSV2.zip

**R1**

Latest Firmware
.. _R1_firmware: http://download.robo3d.com/firmware/R1/ROBO3DR1V3_06_11_2015.zip

Older Versions:
No Auto Level BETA
.. _R1_Old_firmware: http://download.robo3d.com/firmware/R1/ROBO3D_BETA_6_10.zip

R1 with Auto Level and 5/16 inch Rods
.. _R1_5_16: http://download.robo3d.com/firmware/R1/Auto_Level_7_17_516inch_.zip

R1 with Auto Level and 8mm Rods
.. _R1_8mm: http://download.robo3d.com/firmware/R1/ROBO_3D_Auto_Level_7_17_8mm.zip

--------------
Prepare to Upload Files
--------------

Arduino is free to download from www.arduino.cc
..note :: Use 1.6.9 - Arduino 1.6.10+ has an error compiling our firmware. This version is for windows.
.. Arduino: https://www.arduino.cc/en/Main/OldSoftwareReleases#previous

1. Please download and install arduino software.
2. Download the firmware for your printer from the links above.
3. You will need to find the file path for where arduino is looking for sketchbooks, open the arduino software.
4. Go to file, preferences, and make note of the sketchbook location on the top of the preferences window ( by default in Windows it is C:\Users\UserName\Documents\Arduino )
5. Navigate to the Zip file you downloaded, open it
6. Extract the contents in the Zip file and put it where your arduino software is looking for sketchbooks from Step 4.

.. note:: It's important to extract the zip file into the arduino sketchbook folder and NOT into the Library folder. This will cause an error during compiling

--------------
Uploading the Firmware
--------------

1. Make sure your computer is connected to the printer via USB cable. You can leave the power cord unplugged for this procedure.
2. Do not connect Repetier, Matter Control or any other software system to your printer.
3. Close all arduino Instances and Restart the arduino software.
4. Under Tools choose Board and then **"arduino mega 2560"**
5. Under **Tools** choose **Port** and choose the option associated with your printer (will probably be the only option, if not, unplug your printer and see which option goes away).
6. Under **File**, choose **sketchbook**, and then choose **"Your Firmware Name"**.

.. note:: You may need to restart the arduino software for it to see the new sketchbook you added

7. Now hit the **upload** button in the arduino software. This is the **green arrow** pointing to the right at the top of the arduino software window.
8. When the firmware is finished uploading, the arduino software will say **“Done Uploading"**

**You are all done!  Your software should confirm the updated firmware and you're good to go.**
