# xwing-templates
X-wing templates and tokens for laser cutting

acrylic settings on the cutter
==============================
BLACK (probably wrong)
-----
cutting (with paper): 10mm/s 80% pow
rastering: 300mm/s 30% pow, interval 0.1
score: 230mm/s 25% pow

trans grey/bronze
----------
cutting (with paper): 12mm/s 80% pow
rastering (engrave): 280mm/s 30% pow, interval 0.1
score: 231mm/s 20% pow

bamboo
----------
cutting: 12mm/s 80% pow
rastering (engrave): 300mm/s 30% pow, interval 0.1
score: 235mm/s 20% pow

SIZES (for scaling after importing to the laser)
=====
The size in mm in inkscape is the real size. Scale it to this same
size again after importing to rdworks.

Set-up
======
Focus the laser first!
Uncheck "laser through mode" unless you want to try lower power at corners
Ignore the second laser boxes - we only have one

Saving files
============
Save as dxf, untick robo master and lwpolyline (probably)

Troubleshooting
===============
Ensure the cutter is on and the emergency stop isn't triggered
Use COM7 if you have to reconnect

Don't use the bottom part for when you're engraving - that's for altering speed around corners etc.
There's a setting to stop the cutter sw from joining nearby paths.
You'll need it when you import intricate stuff.

Don't forget to re-scale once you get it in the sw.
Last time I used the long range ruler as the tallest thing in the image,
so I could scale the image height to 300.1mm (after locking height to width).
This was maybe a shade too short with kerf considered. 300.5mm?

Use the offset tool (top bar, 2/3 towards the right) to deal with kerf.
0.1-0.05mm is probably enough offset, and use auto in/out.
