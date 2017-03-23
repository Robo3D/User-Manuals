.. Sphinx RTD theme demo documentation master file, created by
   sphinx-quickstart on Sun Nov  3 11:56:36 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=================================================
Cura for Robo
=================================================
To get your 3d prints out looking great, Cura for Robo Desktop Software is the recommended software. This software takes your 3d models, and turns them into a language that the Robo C2 can read, and uses it to produce an object. 

For the Quick Start Guide on using Cura for Robo, click this link (https://www.robo3d.com)

Get Started
-----------

To Download Cura for Robo, click this [link](https://www.robo3d.com)

Requirements

 1. Operating Systems
  * Windows Vista or higher, 64 Bit
  * For Mac instructions, follow this link (https://www.robo3d.com)
  
 2. Hardware
  * OpenGL 2 compatible graphics chip
  * Intel Core 2 or AMD Athlon 64 or newer 

Installing and Setup

 1. Starting Cura for Robo for the first time
  * After installing Cura for Robo, go ahead and open the application from your applications folder (or wherever you have installed it).
 
 2. Selecting a printer
  * The first time you open Cura for Robo, you will see a Add Printer Wizard window. Here is where you will select which printer you have by selecting either the Robo C2 or the Robo R2. Once selected, click the 'Add Printer' Button and your profile will be saved with the correct settings for your printer for optimal printing.

.. image:: images/Add-Printer.PNG
   :alt: Add Printer Wizard
   :align: center

Overview

This is the main view of Cura for Robo. You can reference back to it if you ever need a quick refresh of where things are located within the software.

.. image:: images/Interface2.jpg
   :alt: Interface
   :align: center
   
1. Loading a model
 * Click on the 'Open File' icon at the top left of the screen. Find your .stl file you would like to load and open it. Once this is done, the model should appear on the build platform in the main viewer. 
 
.. image:: images/Load-File.png
   :alt: Load File
   :align: center 
  
* Note; you can also simply drag and drop an .stl file directly on the main viewer to load it onto the build platform
  
 2. Selecting Material
  * Once your model is loaded, the next option you will need to select is your material. Make sure the material you select is the same one that is loaded into your printer. 
 
 3. Selecting a Profile
  * Next, click on the dropdown menu marked 'Profile'
  * Here, you will see different profile settings that will determine the quality of your print. 
  * Select the profile desired - Low, Medium, High, Ultra High Quality. 
  
.. image:: images/Profile-Settings.png
   :alt: Profile Settings
   :align: center   
 
* Below the Pofile settings, you will find the simple recommended print settings. Here you can change infill density, as well as using print build plate adhesion for better adherance on your first layer, and support structure for generating scaffolding to support overhangs and bridges. 
 
.. image:: images/Recommend.JPG
   :alt: Recommended Settings
   :align: center  
 
 4. Saving a File
  * In the bottom right corner of the main window, you will see a 'Save to File' button. Once your satisfied with your model and settings, go ahead and save your file. Note: if you have a USB flash drive inserted, you can save directly to the drive with the same button.
  
.. image:: images/Load-File.png
   :alt: Load File
   :align: center 
  
Using Cura for Robo
-----------

Adjusting the Model
 1. Move
 2. Scale
 3. Rotate
 4. Mirror

Viewing the Model
 1. Solid
 2. X-Ray
 3. Layers

Settings
-----------
recommended vs custom

Quality

Shell

Infill

Material

Speed

Travel

Cooling

Support

Platform Adhesion

Connecting a Printer via Wifi
-----------


Printing a File
-----------
Once you have a file you are excited to start printing, there are a few ways to get your gcode file onto printer.

From Cura for Robo

USB

Save and upload via web interface

Downloading and importing a file into the software
   - Open your web browser and go to a 3d file sharing site. We recommend either www.thingiverse.com or www.youmagine.com for getting free, online 3d models.
   - Browse around and choose a model you like
   - Download the .stl version of the 3d model and save it somewhere you can retrieve it easily on your computer
   - In your Cura for Robo Desktop Software, click on the ‘Load’ button and choose your .stl file you just saved. This will insert your model onto the platform in the software.

Preparing a 3D Model
   - Once your 3d model is inserted into the software, go ahead and select the settings you want your 3d model to be prepared
   - The 3d model will automatically generate with the setting you have selected
   - Press ‘save to disk’ and the model will automatically save to your USB drive you have inserted, or, if there is no inserted USB drive, save it in a folder of your choice.
   - Before taking out your USB drive, make sure to eject it safely

From Model to your printer
   - There are two ways to get a file from your computer to you Robo C2 3D printer. Note that a 3d printable file is a .gcode file that you just created from the Cura for Robo desktop software

Printing from USB Drive
   - If you have saved your file to a USB drive, simply put the USB drive into the slot on the 	front of your machine
	- Tap on the upper left file icon
	- The printer will automatically search through your USB drive and display all of the 3d 	printable files
	- Select the file you want to print, and press ‘print’

Uploading to cloud storage
   - Once you have your 3d printable file, upload it to your same cloud storage you set up 	in your Robo App earlier.
	- In the Robo App, go to your dashboard
	- Tap on the cloud storage icon you saved your file to
	- Once in your cloud storage, find the file you just uploaded, and tap on it. This will 	bring you to a print page.
	- Select which printer you want to print to and tap ‘print’. 

