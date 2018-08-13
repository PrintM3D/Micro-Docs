# Steps to Calibrate the Nozzle Tip for the M3D Micro/Micro+/PRO

**STEPS TO CALIBRATE THE NOZZLE TIP FOR THE M3D Micro/Micro+/PRO**

1. Go the M3D PRO software spooler. You can get access to the spooler by going to the “Show Hidden Icons” on the bottom right corner of your computer screen that has a symbol “^” \(Figure 1\).

![](https://support.printm3d.com/scripts/file.php?view=Y&file=275bfcd3345bc4d2c060060005242c28)

Figure 1: Access to M3D PRO spooler

1. Once into the spooler, click on view and then click on Show Advanced Option \(figure 2\).

![](https://support.printm3d.com/scripts/file.php?view=Y&file=f07d84a91f37dc462c6d9ad9bda85f28)

Figure 2: Advanced Options for the M3D PRO Spooler

The following window will open \(figure 3\):  
 

![](https://support.printm3d.com/scripts/file.php?view=Y&file=22012573e74e925a1ba64cd748284372)

Figure 3: Spooler window showing all the advanced options

1. Now click on Control This Printer tab to control the printer using the spooler so that you can heat the extruder, lower the nozzle, move the printer in X and Y axis, etc \(figure 4\). Type in the G-code G28 to move the print nozzle to the center of the print bed.

![](https://support.printm3d.com/scripts/file.php?view=Y&file=99a52c14c5df310cb1785005e6a1bb42)

Figure 4: Spooler window showing the “Control This Printer” tab

1. Take a small piece of A4 size paper \(100 microns\), figure 5 and slide it under the nozzle.

![](https://support.printm3d.com/scripts/file.php?view=Y&file=2eb6c513bbd92e14fb3e2d42e3cba24f)

Figure 5: Small A4 size paper \(100 microns\) – A sticky note sheet  
 

1. Lower the Z by clicking on -Z such that the A4 size paper just scraps the nozzle tip when moved between the nozzle tip and the print bed. If the paper is too tight to slide in, raise the nozzle. If the paper slides easily without any scarp with the tip feel, then lower the nozzle. You may want move Z by 0.1, 1 or 10 units based on the situation and your judgement \(figure 6\).  NOTE: While lowering the Z, the system might prevent you from lowering the Z-axis any further. In such case, enter the G-code M1012 in the manual insert G-code tab and you should be able to move the Z-axis further down.

![](https://support.printm3d.com/scripts/file.php?view=Y&file=4de33fec23b97d0a39b9c65b4e38764b)

Figure 6: Spooler window showing the +Z and -Z tab to lower or raise the print head/nozzle

1. Once the nozzle tip is at the correct height \(paper scrapping the nozzle tip\), type in the G-code G33 in the manual insert G-code tab and click on send. This will store the offset values for all the corners in the system \(figure 7\) – Next Page.

![](https://support.printm3d.com/scripts/file.php?view=Y&file=624966d2a21638441842708c2e8098ad)

Figure 7: Spooler window showing how to enter the manual insert code such as G33 to store the offset values

 7.  To get access to the functions using the GUI, click on the Release Printer tab \(figure 8\).

![](https://support.printm3d.com/scripts/file.php?view=Y&file=2697d9731b66e095420f21ac2296aa6e)

Figure 8: Spooler window showing how to release the printer from spooler so that the printer can be controlled by the GUI

