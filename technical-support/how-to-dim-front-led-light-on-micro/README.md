# How to dim front LED light on Micro

**Dimming front LED light**

If you would like to dim the front LED of your Micro printer, you can send a simple gcode through the spooler to do so. This process does not work for a Micro+ however this feature will be added in a future release of our software for Micro+ printers.

**The procedure**

1. With printer on and connected, click the gear in the upper right hand corner to access settings  ![](https://printm3d.com/solutions/assets/img_55afa90b0a79a.png)
2. Navigate to the advanced settings tab and click the checkbox labeled "Expert Mode" to open the Spooler  ![](https://printm3d.com/solutions/assets/img_55afa8ba128e1.png)
3. Find the manual insert gcode text field   
 

   ![](https://printm3d.com/solutions/assets/img_566ae313de746.png)

4. Enter gcode: M420 t125 for half the LED strength

Note: You can change the strength of the LED by changing the t value between 0 - 255. For example, 0 = LED OFF, 255 = LED ON, 125 = LED HALF ON. Adjust LED with the t value that works for you.

