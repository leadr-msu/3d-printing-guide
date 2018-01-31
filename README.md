# 3D Printing Guide

## Open 'Cura'
This is where you will adjust the size and orientation of your model for printing. 

First you need to load a .obj file (this is the finished model product). Your model should not have any gaps or holes that could cause issues with printing. 

When you have your object selected, three icons in the bottom left corner will appear: Rotate, Scale, and Mirror

### Rotate
The bottom left icon is for rotate. The top option allows you to have ‘Cura’ automatically lay your object flat. This will assist in the printing process. You can also manually adjust the orientation of the object with the three adjustment circles that appear. Normally it allows you to adjust in 15 degree increments, but if you press ‘shift’ while rotating, you can rotate at 1 degree increments. 

### Scale
The center bottom icon is for scaling your object. You can either adjust the size of your object based on millimeter measurements or by manualing dragging the scale bar axis (x, y, z) options. You also have the options to have ‘Cura’ scale your object to the largest maximum size to print. 

### Mirror
This option will allow you to automatically flip your object (i.e. mirror) your object along either the X, Y, or Z axis. 

## Adjusting the Print File
Within the toolbox on the left side of the screen, you are able to adjust many different options that will affect the print quality, fill, speed, and temperature. 

### Quality

#### Layer Height (mm)
This is the most important setting for determining the quality of your print. Normal quality prints are 0.1 mm, high quality prints are 0.06 mm. You can go up to 0.25 mm with the Ultimaker for a very fast print at a very low quality.

#### Shell Thickness (mm)
This thickness is of the outside shell in the horizontal direction. This is used in combination with the nozzle size to define the number of perimeter lines and the thickness of those perimeter lines. 

#### Enable Retraction
This allows for the filament to be retracted when the nozzle is moving over a ‘none-printed’ area. More details about the retraction can be configured in the advanced tab. 

### Fill

#### Bottom/Top Thickness (mm)
This controls the thickness of the bottom and top layers, the amount of solid layers put down is calculated by the layer thickness and this value. Having a value a multiple of the layer thickness make sense. And keep it near your wall thickness to make an evenly strong part.

#### Fill Density (%)
This controls how densely filled the insides of your print will be. For a solid part use 100%, for an empty part use 0%. A value around 20% is usually enough. This will not affect the outside of the print and only adjusts how strong the part becomes. 

### Speed and Temperature:

#### Print speed (mm/s):
Speed at which the printing happens. A well adjusted Ultimaker can reach 150mm/s, but for a good quality print, you want it to print slower. Printing speed depends on a lot of factors. So this is one setting that you will experiment with. 

### Support:

#### Support type
This is where you choose between no support type, support through touching the buildplate, or an ‘everywhere’ support type. Touching buildplate only creates support where the support structure will touch the build platform; everywhere support creates support even on top of parts of the model.

#### Platform adhesion type
This is where you will choose between no platform adhesion, a brim platform adhesion, or a raft adhesion. Each of these are different options which help in preventing corners from lifting due to warping. Brim adds a single layer thick flat area around your object which is easy to cut off afterwards, and it is the recommended option. Raft adds a thick raster below the object and a thin interface between this and your object. 

## View Mode
You are able to view your model in a variety of ways including: normal, overhang, transparent, x-ray, and layers. To switch between these options click the icon located in the top right corner of the of the program (see image to the right). 

## Save Model
To save your model you can either go to File → Save GCode, or you can click the floppy disk save icon (Save toolpath option) in the top left corner of the screen (see image below). If you have the SD card plugged into the computer, the ‘save toolpath’ option will automatically save the model to that location. 
