# Button Based Delay
The objective of this lab is to use a button to determine the frequency of the flashes of an LED based on the amount of time that the button is held down for. So if the user holds down the button for one second the the time between flashes would be one second. This is done by using an interrupt triggered by the button that starts a timer which counts the length of time the button is pressed. This length sets another timer that controls the frequency of the LED.

## Processors Used
* MSP430G2553
* MSP430FR6989

## Changes In Code For Different Processor
The G2553 and the FR6989 have very similar code and are done with the same process, however they have different pin assignments which must be changed whens translating code from one board to the other. The other difference is that for the FR6989 you must disable the power-on default high impedence mode.
