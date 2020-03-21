### Bamboo Enclosure for NeoTrellis Grid

#### Laser cutting
SVG files are provided for laser cutting 3mm bamboo sheets.

**IMPORTANT:** SVG scaling can change between software programs. Make sure your dimensions are correct before laser cutting. Try printing the top layer onto paper and check that it fits.

**Cut colour is blue: #0000FF**  
**Engrave colour is black: #000000**  
**Stroke width for cuts is 0.025mm.** This is the width required by the laser cutter I use. (This is what makes the graphics a bit faint looking when editing.)


#### Assembly notes
Look at the provided images to see how the layers fit together, and where to put the Teensy board.  
The design requires that you have the USB extension for the Teensy. It should be screwed in place using very short screws. Start the screws with a hole created by an awl, or you may split the bamboo.  
There is one bamboo layer which has an engraved rectangular recess to accomodate the USB extension PCB. The depth of the engraved recess should be equivalent to at least the thickness of the USB extensions PCB. You may have to experiment with your laser cutter settings to get the right depth.

There are holes for screw inserts in the upper layers. This allows the enclosure to be made into two parts which can be bolted together, allowing access to the Teensy. The layers in each section should be glued together using clamps.

As can be seen in the images, I run the cable from the Teensy to one of the NeoTrellis PCBs underneath one of the supporting struts in the bamboo layer. To do this I had to *carefully* pare away a small section from the bamboo strut using a craft knife.

Do the bulk of any sanding before fitting the electronics.  


#### Assembly options
- You may find that there isn't enough space for the Teensy when assembling the bamboo layers, as the reset button is continually pressed by the layer below. There are a few possible options to overcome this:  

1. Desolder the reset button (after Teensy programming is complete), or:
2. Add a hole in the bamboo layer below the Teensy (base+1) so that is doesn't press on the reset button. This will also give you access to reset the Teensy if required.

- If you make a hole to access the Teensy reset button, you might want to dispense with the screw inserts completely and glue all the bamboo layers together.

- The base+1 layer has holes which were originally for fitting standoffs but were kept for ventilation purposes. You might want to edit these but make sure that the Teensy has some ventilation.

- If you prefer to have the buttons protrude less you can add another top layer, making a total of 7 layers instead of 6.