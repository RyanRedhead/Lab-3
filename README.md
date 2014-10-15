Lab-3
==================
#Purpose

To familiarize with the logic analyzer and create an 8x8 block on the LCD screen.

#Hardware Schematic

![Alt Text](https://github.com/RyanRedhead/Lab-3/blob/master/hardware.jpg?raw=true)

This is an image of the LCD screen on the MSP430 with the pins needed for the logic analyzer.

#Debugging

Choosing the right pins to read for the logic analyzer was a difficult task, mostly guess and check because I wasn't getting results that looked right. In the required functionality creating an 8 by 8 block was difficult because I had to find the correct addresses for it. And still where the block is created is off-center. I could fix this by possible changing the X and Y coordinates I entered.

#Testing Methedology/Results

##Logic Analyzer

Here are two of the completed tables for the logic analyzer portion that look at the command/data bits.

![Alt Text](https://github.com/RyanRedhead/Lab-3/blob/master/Table%202.PNG?raw=true)

![Alt Text](https://github.com/RyanRedhead/Lab-3/blob/master/Table%201.PNG?raw=true)



![Alt Text](https://github.com/RyanRedhead/Lab-3/blob/master/Image1.jpg?raw=true)

The first image shows a single clock period of my MSP430 chip at 934ns or 1.07 MHz.

![Alt Text](https://github.com/RyanRedhead/Lab-3/blob/master/Image2.jpg?raw=true)

The second image represents the command/data bit followed by the 8 data bits sent to the MSP430.

![Alt Text](https://github.com/RyanRedhead/Lab-3/blob/master/Image3.jpg?raw=true)

In this image, the reset was measured at 1.148 micro seconds.

##Required Functionality

![Alt Text](https://github.com/RyanRedhead/Lab-3/blob/master/Required.jpg?raw=true)

Here the required functionality is shown on the LCD screen, displaying an 8 by 8 block.

#Observations/Conclusions

This lab was alot of guess and check for me, I'm still not quite sure how most of the original Lab3.asm file works. For A functionality I would've implemented each button to a pin and checked to see if it was pressed or not, if it was pressed it would shift the block over by changing the cursors.




Mega Prelab-Check
Logic Analyzer-Check
Required Funct. -Check

Doc: Dr Coulston helped explain the logic analyzer portion and the difference between the command and data commands.


