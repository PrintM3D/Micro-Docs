# Printing with Phantom White ABS \(a.k.a. HIPS\)

As you might know, ABS temperature for the Micro is approximately 265C - 270C. This high temperature combination with near perfect offsets can lead to the nozzle digging/burning/damaging the buildtak sheet. You can dramatically improve print success with lower quality print settings because it nearly eliminates warp. In order to print with Phantom White ABS please try the following: 

1. First raft layers must use wave bonding.
2. Must use raft.
3. First layers of raft must not be higher than ~265-270C or buildtak gets damaged. 
4. Go into Expert Mode \(M3D Spooler\)
5. Turn fan off by clicking the Fan Off button
6. Turn up temps dramatically on first 5 layers after raft \(285-290C\). Type "M104 S285" in the Manual Insert G Code textbox.
7. CAN use the perfboard \(no buldtak\) option for phantom white ABS! 
8. Do not perform any calibration without the buildtak print surface, or it could severely damage the perforated print bed.

Advantages:  Strong, good looking, low odor, easily solvent smoothed

PIC Below:

Left \(large octopus, 275C hips, no raft, damaged buildtak and skipped first layers\).

Right \(same, first layers 285C, raft in perfboard, much cleaner\)

![](https://printm3d.com/solutions/assets/img_559249ca3b3aa.png)Updated: Mar 22 \(3 months ago\)

