# Print Options

To view more print options, click "Print", then click "More Options..." to modify more print options like wave bonding and support material. Below, we have listed some general information about these settings and features. 

![](http://m3dhelp.com/support/assets/img_556769090501a.png)

**Printer:** Displays the printer's serial number

**Current Filament:** Displays the filament you have loaded through the internal port or through the external port. 

**Print Quality \(layer resolution\):** There is a range of 100 microns \(High quality layer accuracy\), 200 microns \(Medium quality\), and 300 microns \(Low quality\). If you choose a larger layer height, it will print faster but have less resolution per layer. Lower layer resolution isn't necessarily better, especially for materials that warp more easily.

**Fill Density:** There is a range of Hollow thin walls \(1 wall\), Hollow thick walls \(2 walls\), Low infill, Medium infill, and High infill. Changing the infill will change the estimated completion time of the print job, as well as determine how hollow or hard a printed object can be. For example, small, thin limbs my require more infill to prevent them from snapping into pieces, while large vases may not require any infill. Poor bridging happens for the top layers of hollow prints, because our software is not optimized for 90 degree overhang. In a perfect world, the extruder should slow down and the fan speed should turn up so that we can get an instantly cooled top layer. Try printing with low infill instead of hollow, and you should have much more success printing the top layer of the model. 

**Support Material Feature:** Printing a model from the bottom up, as with FDM, means that any significant overhangs will be printed in the air, and most likely droop or not print correctly. Choosing support material will add additional structures around the model which will build up to then support the overhanging part.

![](https://printm3d.com/solutions/assets/img_558189e02313b.png)

**Model-on-model support Feature:** Choosing model-on-model support material will add additional structures on top of the model below, which will build up to then support the overhanging part.

![](https://printm3d.com/solutions/assets/img_558189ca7448b.png)

**Wave Bonding Feature:** For the very first layer, anchor points are created approximately every 5mm to ensure the model sticks to the print surface. We recommend using this feature for large prints to prevent the first layer from warping/peeling. 

![](http://m3dhelp.com/support/assets/img_5575ffc072ded.png)

**Raft Feature:** The raft is a support layer underneath the model. Printing without a raft may fail and is recommended only for advanced users. Printing without a raft requires the bed level to be accurate to ensure warping/peeling of the entire model does not occur. 

