# Lab 1: Button Blink

## Summary
 There are two programs made for two different boards the MSP430F5529 and the MSP430FR2311. Each of the programs use a button located on the Lauchpad designated by a pin to turn of the lit LED on the given board.

## General Functionality
 The two programs included  use a basic button to turn off an LED as you hold it. This is done with a if statement checking if the button is pressed when it is pressed the if statement is true and shuts off the light.
 
## Inputs and Outputs

### MSP430F5529
 INPUTS: P2.1-Tactile Button
 OUTPUTS: P4.7-Green LED
 
### MSP430FR2311
 INPUTS: P1.1-Button  
 OUTPUTS: P1.0-Red LED
 
## Authors

   Author: Kieran O'Connor  
   Last Editted: 9/19/2018

# Button Blink
Now that you have looked at blinking the LED from some built in delay, but what if we wanted to control the state of the LED by a button? You may think "Why would I need a Microcontroller to perform the job of a switch?". And that is where you come in. The bare minimum for this part of the lab is to essentially replicate a switch with your development board.

# YOU NEED TO CREATE THE FOLLOWING FOLDERS
* MSP430G2553
* MSP(FILL IN THE PROCESSOR YOU ARE USING)

## README
Remember to replace this README with your README once you are ready to submit. I would recommend either making a copy of this file or taking a screen shot. There might be a copy of all of these README's in a folder on the top level depending on the exercise. Make sure you talk about how your button is configured (momentary or continuous. Normally open or closed. Does the button press indicate when the LED should be on or off.)

## Extra Work
What can we do to make this a little bit more worthy of needing a microcontroller.

### Button Based Speed Control
Much like the UART controlled speed, what if you could cycle between speeds based on a button press? The speed could progress through a cycle of "Off-Slow-Medium-Fast" looping back when you hit the end.

### Color Change
What if upon a button press, the LED which was blinking changed. Some of the development boards contain two LEDs, so you could swap between a Red and a Green LED.
