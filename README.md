# Various Inkscape extensions

 - Raster 2 Laser GCode generator
 - Added Mach3 fonctionnality - By CSONNECK --> https://www.youtube.com/watch?v=I0V7Ks5T5Sk
 
#Descriptions
- Raster 2 Laser GCode generator is an extension to generate Gcode for a laser cutter/engraver (or pen plotter), it can generate various type of outputs from a simple B&W (on/off) to a more detailed Grayscale (pwm)

#Installing:

Simply copy all the files in the folder "Extensions" of Inkscape

>Windows ) "C:\<...>\Inkscape\share\extensions"

>Linux ) "/usr/share/inkscape/extensions"

>Mac ) "/Applications/Inkscape.app/Contents/Resources/extensions"


for unix (& mac maybe) change the permission on the file:

>>chmod 755 for all the *.py files

>>chmod 644 for all the *.inx files



#Usage of "Raster 2 Laser GCode generator":

[Required file: png.py / raster2laser_gcode.inx / raster2laser_gcode.py]

- Step 1) Resize the inkscape document to match the dimension of your working area on the laser cutter/engraver (Shift+Ctrl+D)

- Step 2) Draw or import the image

- Step 3) To run the extension go to: Extension > 305 Engineering > Raster 2 Laser GCode generator
          For Mach3 --> See my video on Youtube :https://www.youtube.com/watch?v=I0V7Ks5T5Sk
                    Homing : No Homing
                    G92 : None (Mach3)
- Step 4) Play!




#Note
I only modified the following files:
 - raster2laser_gcode.inx
 - raster2laser_gcode.py
 
 Enjoy and Share
