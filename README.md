# xwing-templates
X-wing templates and tokens for laser cutting

## Cutting instructions
1. Create vector file in inkscape
2. Convert all objects to path and remove all groupings from vector file
3. Save svg to a USB and transfer to cutter computer
4. Open svg in lightburn
5. Set cutting properties for each colour (see below for recommendations)
6. Turn on cutter and click "transfer" to send file.
6. Prepare cutter and material


## Recommended cutter settings
Always check the hackerspace whiteboard for tips!
The laser seems to have weakened over time
Remember that the cutter uses heat and so will cut deeper in some areas and with close lines
Keep designs small and compact to minimise drift
Cut/score slower than 50mm/s if you have sharp corners or the laser will overshoot
Don't exceed 90% power (32mA)

TODO outline the "big card" on the 1 straight template - or change colour so it can be cut AND rastered

## Inkscape weirdness
Inkscape considers line thickness when you define a shape
Obviously this makes no sense w.r.t a laser cutter, so either use REAL THIN lines or
use single lines to construct shapes

## SVG File Colours
Red: Cut
Black: Raster
Green: Engrave (score)

### Acrylic
#### Trans red
raster: 200mm/s 30%pow interval 0.1 crosshatched
cut:    6mm/s 95%pow
score:  200mm/s20%pow???

## Cutter Preparation
Turn on both on switches and ensure Estop isn't pressed
Focus laser after placing material: balance bent metal piece off laser head and raise bed until it falls
Move head with arrow buttons to start position and hit origin
Test the bounding box before cutting


## Troubleshooting
Ensure the cutter is on and the emergency stop isn't triggered
If file won't transfer, try restarting laser and disconnecting/reconnecting USB cable
Use COM7 if you have to reconnect(?)
