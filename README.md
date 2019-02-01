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
Remember that the cutter uses heat and so will cut deeper in some areas and with close lines
Keep designs small and compact to minimise drift

### Acrylic
#### Trans red
raster: 200mm/s 30%pow interval 0.1 crosshatched
cut:    6mm/s 95%pow
score:  ???

#### Trans blue
raster: 200mm/s 30%pow interval 0.1 crosshatched
cut:    7mm/s 95%pow
score:  ???

#### White
raster: 280mm/s 30%pow interval 0.1
cut:    8mm/s 95%pow //12mm/s 80%pow
score:  ???

#### Black (probably wrong)
raster: 300mm/s 30%pow interval 0.1
cut:    10mm/s 80%pow
score:  230mm/s 25%pow

#### Trans smoke (dubious)
raster: 280mm/s 30%pow interval 0.1
cut:    12mm/s 80%pow
score:  230mm/s 25%pow

### Bamboo
raster: 300mm/s 30%pow interval 0.1
cut:    12mm/s 80%pow <- can probably go lighter
score:  235mm/s 20%pow

### Mango kmart chopping board
raster: 230mm/s 50%pow interval 0.1 <- too harsh, try 40%? 
cut:    good luck mate
score:  ???


## Cutter Preparation
Turn on both on switches and ensure Estop isn't pressed
Focus laser after placing material: balance bent metal piece off laser head and raise bed until it falls
Move head with arrow buttons to start position and hit origin
Test the bounding box before cutting


## Troubleshooting
Ensure the cutter is on and the emergency stop isn't triggered
If file won't transfer, try restarting laser and disconnecting/reconnecting USB cable
Use COM7 if you have to reconnect(?)
