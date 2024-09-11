# Week-1 - First Code

Written by: Jack Jewison and Halden Kerzner

Updated: September 11th, 2024 at 4:00pm

Dependent Libraries:
<msp430.h>
<GPIO_driver.h>

Our code causes the buttons on either side of the board to turn on and off the red and green LEDs at the bottom of the board. When the button on the left is pressed, the red LED will turn on and off. When the button on the right side of the board is pressed, the green LED will turn on and off. The program receives inputs via pins 4.1 (BUTTON1) and 2.3 (BUTTON2) (ie. the buttons), and transmits an output signal (power) to pins 1.0 (RED_LIGHT) and 6.6 (GREEN_LIGHT) respectively. This modified version of the original utilizes a header file titled, "GPIO_driver.h", in order to simplify the functions in the main file. Both the driver files and main file are listed in this branch.
