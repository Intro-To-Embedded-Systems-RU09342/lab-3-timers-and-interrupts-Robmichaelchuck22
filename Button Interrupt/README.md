# Button Interrupt
The objective of this lab is to toggle an LED upon the press of a button without the medothod used in previous labes of contantly checking if the button is being pressed. Instead for this lab we use an inturrupt generated by the press of the button. The LED is turned on and when the button is pressed it toggles the state of the LED.



## Processor Used
* MSP430G2553
* MSP430FR6989


## Changes in Code for Different Processors
The G2553 and the FR6989 have very similar code and are done with the same process, however they have different pin assignments which must be changed whens translating code from one board to the other. The other difference is that for the FR6989 you must disable the power-on default high impedence mode.


