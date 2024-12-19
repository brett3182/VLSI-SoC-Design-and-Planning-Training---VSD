# VLSI-SoC-Design-and-Planning-Training---VSD

## #**Day 1 Labs**
Synthesis of picorv32a completed: 
https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/layout.png?raw=true
![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/Synthesis%20Successful.png?raw=true) 

Report and Flop-ratio: 
![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/Flop%20ratio.png?raw=true) 

**Flop Ratio** = Number of D Flip Flops / Number of Cells  
= 1613 / 14876  
= 0.1084

Hence, the flop ratio is 10.84% 

## #**Day 2 Labs** 
Floorplan of picorv32a completed:

![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/Floorplan%20successful.png?raw=true) 

Dimensions of the die: 

![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/Dimensions%20of%20the%20die.png?raw=true) 

Height = 660.685um, Width = 671.405um 

Area = 660.685um x 671.405um = 0.443mm² 

Layout of picorv32a viewed in magic: 

![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/layout.png?raw=true) 

Zoomed in to view the pins (placed equidistant), decaps and the horizontal and vertical metals. Their properties can be seen in the tkcon window using 'what' command

![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/horizontal%20and%20vertical%20metal.png?raw=true) 

The standard cells are present at the bottom left corner 

![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/standard%20cells.png?raw=true) 

After floorplan, placement is carried out
Placement of picorv32a successful: 

![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/Placement%20successful.png?raw=true) 

Placement ensures that the standard cells are positioned in their respective rows without any DRC errors; however, since it follows global placement, legality may not be maintained.

![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/Standard%20cells%20placed.png?raw=true) 
![image alt](https://github.com/brett3182/VLSI-SoC-Design-and-Planning-Training---VSD/blob/main/images/placed%20sc%20zoomed.png?raw=true)





