# jFET3x_Bass_overdrive
Bass overdrive pedal 

![alt text](https://github.com/SlowProject/jFET3x_Bass_overdrive/blob/main/pics/3Dfront.jpg)  

PCB PADS:  
-	G1 and G2: ground pads (both connected to the ground plane of the PCB)  
-	9V: +9V  
-	IN: audio IN  
-	OUT: audio OUT  
-	LED: to be connected to the anode (+) of a LED; the cathode must be connected to ground. Not necessary if you use a 3PDT adaptor (which includes LED resistance and LED pads).

See https://github.com/SlowProject/3PDT_PCBforGuitarPedals for the 3PDT-switch adaptor PCB.  
Otherwise you can connect the 3PDT switch following this [schematics](https://github.com/SlowProject/Fuzz_Jordan_guitar_pedal/blob/main/Fuzz%20mlm%20vs1-imagen-wiring%20to%203PDT%20switch.jpg)  

NOTE: Set the bias voltages at the drains of Q1, Q2 and Q3 using the corresponding trim pot (TRP1, TRP2 and TRP3). Around 5V is fine, but experiment!
