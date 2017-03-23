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

**Requirements**

 1. Operating Systems
  * Windows Vista or higher, 64 Bit
  * For Mac instructions, follow this link (https://www.robo3d.com)
  
 2. Hardware
  * OpenGL 2 compatible graphics chip
  * Intel Core 2 or AMD Athlon 64 or newer 

**Installing and Setup**

 1. Starting Cura for Robo for the first time
  * After installing Cura for Robo, go ahead and open the application from your applications folder (or wherever you have installed it).
 
 2. Selecting a printer
  * The first time you open Cura for Robo, you will see a Add Printer Wizard window. Here is where you will select which printer you have by selecting either the Robo C2 or the Robo R2. Once selected, click the 'Add Printer' Button and your profile will be saved with the correct settings for your printer for optimal printing.

.. image:: images/Add-Printer.PNG
   :alt: Add Printer Wizard
   :align: center

**Overview**

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
  
.. image:: images/Print.JPG
   :alt: Save File
   :align: center 
  
Configure and View the Model
-----------

To further configure your model for printing after you have loaded it onto the build platform, click on the model so it becomes highlighted.

**Configuring the Model**

1. Move
 * You can move your model around the build platform with the Move tool. Either by the 'click-and-drag' method, clicking the arrows projecting from the model, or entering values in the fields provided.

.. image:: images/Configure.JPG
   :alt: Configure Model
   :align: center  

2. Scale
 * Selecting the Scale tool will allow you to scale the model in 3 different ways
 * Dragging the handles located on the model itself will scale the model in whichever way the handle is oriented
 * Entering the size desired into the number field scales the model into an exact dimension desired
 * Selecting a percentage to scale will allow you to scale the model by a certain percentage based on its original dimensions
 * Note; if you want your model to come out uniform, select the 'Uniform Scaling' check box when scaling
 
.. image:: images/scale.png
   :alt: Scale Model
   :align: center
 
3. Rotate
 * Selecting the rotate tool will bring up different ways to rotate your model
 * You will notice colored rings around your model for different axis. Click and drag one of these rings to rotate in that direction
 * Also shown is the 'Reset' and 'Lay Flat' buttons to orient you model in a way that best suites you
 
.. image:: images/rotate.png
   :alt: Rotate Model
   :align: center

4. Mirror
 * The Mirror tool will allow you to mirror the model in the X, Y, and Z axis. 
 * Simply click on one of the arrowheads that pop up on your model to mirror it in that direction.

**Viewing the Model**

Once you have satisfied all of your configuration and profile settings, you can view the model in layer mode. Layer mode allows you to inspect the way your model is sliced and will be printed. It is usually best to inspect your model this way to see if it will be printed the way you are intending.

.. image:: images/View-mode.png
   :alt: View Mode
   :align: center

1. Solid
 * Solid view is the deafualt view when the program is started. You can view the digital model to see if it is created like it was intended, and also see where it might have imperfections when examining it. 
 * The model will be colored yellow if it is selected and within the usable print area, and grey if it is either deselected or out of the printable build area.
 
2. X-Ray
 * With X-Ray view, your model will show gaps and intersections throughout your model. These will be shown in red. 
 * If an error is located in your model, go ahead and adjust it in your 3d design software and reload the model to check if the error has been fixed.

3. Layers
 * Layers view is one of the more important views to check before you start printing your model. The Layers view is a virtual representation of the where your nozzle is going to move throughout the print process of the physical model.
 * When the Layers view is selected, a slider will appear beneath the button.
 * Use the slider to look through your layers one by one and see how your model will be built.
 * You can also input a layer number to jump directly to the specified layer of your model.
 * Note: Every time a setting is changed, the view has to be completely reloaded with the new settings in layer view.
 
.. image:: images/layer-view.png
   :alt: View Mode
   :align: center

Settings
-----------
recommended vs custom

**Quality**

**Shell**

**Infill**

**Material**

**Speed**

**Travel**

**Cooling**

**Support**

**Platform Adhesion**

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

