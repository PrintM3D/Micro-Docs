# Printer Not Extruding/Underextrusion/Overheating

**Desciption of Problem**

If the printer does not extrude at all, you either have a clog in the nozzle or the extruder motor is problematic. 

**Causes** + _Solutions_

* **Software** - Please upgrade to the latest beta version software.
  * _Solution:_ Download the latest beta version for [MAC](https://www.dropbox.com/sh/maf6kv4c80fyu0b/AACLs90jq_mmgA04DpYmiDxCa/Software%20-%20Mac/Mac%20Software%20-%202015-11-23%20-%20El%20Capitan?dl=0) or [Windows](https://www.dropbox.com/sh/maf6kv4c80fyu0b/AAAPXIomuyrv8poKvInJ-Pu-a/Software%20-%20Windows/Windows%20Software%20-%202015-11-23%20-%20Processing%20fix?dl=0)  
* **Overheating extruder** - The print head may be experiencing an overheating effect which causes the printer to have difficulty extruding material. This can also cause the filament to get pushed back up into the extruder gear. You can remove the wallE cover to verify if the filament is wrapped around the gear like the image below.

![](https://printm3d.com/solutions/assets/img_55957424c2c29.png)

* _Solution:_ If this occurs, it is very likely that the fan is not running while printing. Please refer to the fan section below.

**Extruder**  
The extruder motor can wiggle out of the metal housing position inside the print head.

Extruder gear issues include:

Jam in extruder gear. 

Remove cover and clean out filament from the print head. 

Here are the recommended in-field repairs for motors that have moved out of the housing E:

Recommend using a small screwdriver to push it forward back into its housing and then applying some super glue to hold it in place.

-Take a look at this forum thread \(https://printm3d.com/portal/forum/index\#/discussion/492/superglue-the-motor\) to see a visual of how your motor should look, and where to apply the superglue.  
-As long as the motor is pushed all the way forward, you should be able to apply the superglue to all the circled points shown in the image.

Push motor into HousingE and retain with small screws, glue. 

-Use the following instruction to replace the original extruder core \([How To Guide: Extruder Core Replacement](http://m3dhelp.com/support/article.php?id=15)\)  
-Add screws in the middle of this process. \(see example image below\)

Purchase a replacement extruder core 

-Use the following instruction to replace the original extruder core \([How To Guide: Extruder Core Replacement](http://m3dhelp.com/support/article.php?id=15)\) 

![](http://m3dhelp.com/support/assets/img_5567ed856eb6b.png)

**Fan**  
The fan can either be disconnected \(as seen in the image below\), slow, or dead. Also, the fan needs to have the correct code to operate properly and not fail prematurely.

* **The fan is on full blast and very noisy OR the wrong M-code was set for the fan** - Both of these issues can be eliminated by software fix. Please download the latest beta version for [MAC](https://www.dropbox.com/sh/maf6kv4c80fyu0b/AABjwVY7WmwFr7aavB1lF7z0a/Software%20-%20Mac?dl=0) or [Windows](https://www.dropbox.com/sh/maf6kv4c80fyu0b/AACH_cU2QQEIFeVqJ88l5v6ia/Software%20-%20Windows?dl=0) to ensure the m-code will work properly.
  * _Solution:_ Identify which type of Fan logo you have in your printer. &gt;Once you match the logo on the fan to find your fan’s identification code. &gt; Open Settings menu and click Expert Mode to open the M3D Spooler &gt; Type your fan’s identification code in the textbox titled “Manual Insert G-Code” and press enter. &gt; Your fan should now be ready.  ![](https://printm3d.com/solutions/assets/img_55818adf57c82.png)  **Note: If you do not see a logo on the bottom of your fan, this is our newest fan version and should use the code M19007**
* **Fan turning slow** - Filament or a pinched wire may be trapped in the blades. 
  * _Solution:_ Check the fan for any physical obstruction.  
* **Fan not rotating** - The fan could have disconnected wires, a disconnected connector, or might also have a bad position \(too high\) in the extruder housing. 
  * _Solution:_ Please [open the print head cover](https://printm3d.com/solutions/article.php?id=16) and check the fan's connector is attached. It will be the smallest connector with two wires. Try lowering the fan by 1mm increments.  
* **Replacing a Fan** - To purchase a fan, Need instructions to install a replacement fan?
  * _Solution:_ Please view the [How To Guide: Fan Replacement](https://printm3d.com/solutions/article.php?id=73) article. 

**Worst Case Scenario**  
If the fan is connected properly and does not spin at all, it's possible the unit has a shorted PCB circuit board. This requires initiation of a return for repair \(RMA\) process.  
 

**Heater**  
The temperature of for the hot end area might be too cold.

**Troubleshooting: Confirm the Heater is not broken**

1. Load filament as normal. 

![](https://printm3d.com/solutions/assets/img_55b012b8e3ace.png)

2. Open M3D Spooler by clicking the icon in the lower right hand corner. 

![](https://printm3d.com/solutions/assets/img_55b01388cbeba.png)

3. Watch the temperature rise at the bottom of the Spooler window. 

![](https://printm3d.com/solutions/assets/img_55b0132a62c52.png)

4. If the temperature rises to 200C, the heater is working properly. If the temperature does not rise above 50C, then the heater wires might have broken off of the metal contact pad or a wire has been removed from the connector socket.

![](https://printm3d.com/solutions/assets/img_55b016b219329.png)

**Causes** + _Solutions_

**Air Flow** - If the Front Cover of the print head is off the print head, air flow from changing ambient temperature \(external fans or open windows\) might create cold extrusion symptoms.

Solution: Please put the cover on. Otherwise, a replacement front cover can be purchased under warranty with a request to [Technical Support](https://printm3d.com/contact?t=Technical-Support).

**Heater+Rubber Insulator Position** - Heater issues most likey result from the Heater and the rubber insulator are positioned too far up on the nozzle shaft. This can create a cooler chamber at the tip of the nozzle, which will cause thin filament to extrude \(a sign of cold extrusion\). 

_Solution:_ Re-position the Heater to at the tip of the nozzle [\(see correct example\)](http://i.imgur.com/pMMwDF3.png). 

**Low Factory Calibration** - Temperature can be low due to low factory calibration.

_Solution:_ Increase temperature in increments of 10C at a time. Your filament might not be hot enough. Find out how to change temperature and more on [Creating Custom Filament Profiles](https://printm3d.com/solutions/article.php?id=47).

**Heater Fail Error Messages** - Printer will not heat up. First check if the wires are connected and not broken. Second, check if your Expert Mode spooler log says any of the following error codes. Error code “HF:1” = Heater switch failed

Error code “HF:2” = Heater failed  
Error code “HF:3” = Similar to “HF:1” heater is in an uncontrolled state  
_Solution:_  First, try to power cycle the printer \(unplug, and plug back in\). If the error messages occur again then hardware has failed, which means either heater wires are broken or heater controller is fried. Second, confirm the heater wires have not broken or been disconnected on either end. Otherwise, please see the worst-case scenario below.  

**Worst Case Scenario**  
We cannot send a replacement heater element because the calibration values would not match and would potentially cause your printer to not work properly. The heater wires might have been disconnected for some reason. If you find the wires are disconnected or broken, please email us an image through [helpdesk@printm3d.com](mailto:helpdesk@printm3d.com). We will then need to initiate the [Return for Repair \(RMA\) process](https://printm3d.com/solutions/article.php?id=182). 

![](https://printm3d.com/solutions/assets/img_55a70040dc4cb.png)

**Nozzle**  
Nozzle might have particulates that block the nozzle hole.

**Metal particulates** - Metal particulates might be blocking hole at the nozzle tip. 

_Solution:_ Use a steel wire \(any steel wire of ~1 mm should work\) to clean the nozzle, but please take care when removing clogged filament from the nozzle with metal. Although the heater only runs at 5V and you won't get a shock, it may break if metal comes into contact with the wire across the heater's contacts. Continue cleaning the nozzle with a steel wire until it moves freely without encountering any sticky plastic. For a video demonstration of this process \(Thank you Mark Wheadon!\), please view the youtube video here: [https://www.youtube.com/watch?t=213&v=WKIL2AedyMQ](https://www.youtube.com/watch?t=213&v=WKIL2AedyMQ). Recommendation is to purchase a replacement nozzle subassembly. A replacement nozzle subassembly can be purchased under warranty with a request to [Technical Support](https://printm3d.com/contact?t=Technical-Support).

**Loading different materials** - Clogs after switching between materials, especially trying to push pla after another material \(nylon, TPU, ninjaflex, abs\). Non-M3D filament, such as Carbon or wood filled filament was used is NOT covered by warranty.

_Solution:_ Please view the [Switching from ABS to PLA filament type](https://printm3d.com/solutions/article.php?id=48) article to fix. Recommendation is to purchase a replacement nozzle subassembly. A replacement nozzle subassembly can be purchased under warranty with a request to [Technical Support](https://printm3d.com/contact?t=Technical-Support).

**Dirty nozzle tip**

_Solution:_ To clean the nozzle tip, please use the "Remove Filament" function and follow the prompts in the software. Once the filament has been removed, you can take a sponge, a strand of ABS or PLA filament, or something with a textured surface and proceed to wipe it clean since the heater is still on. Please be careful not to burn your fingers.

**Teflon tube jammed or flipped** - The teflon tube might have pushed up into walle and jammed the extruder drive gear. Also, the teflon tube might be flipped so the chamfered end could be on the wrong end. 

_Solution:_ Fix the top hole chamfer so it is round, re-insert, make sure [teflon tube is positioned correctly](http://i.imgur.com/UHzgliq.png). Flip the teflon tube to the chamfered opening. You may need to heat up the nozzle to remove the teflon tube. As a last resort, our recommendation is to purchase a replacement nozzle subassembly. A replacement nozzle subassembly can be purchased under warranty with a request to [Technical Support](https://printm3d.com/contact?t=Technical-Support).

**WallE resistance** - The small black cover on the drive bearing inside the extruder might be screwed on too tight. 

_Solution:_ Remove walle to verify. Sand or file the walle to fix; or send replacement walle once verified.

