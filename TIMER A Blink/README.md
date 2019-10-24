# TIMER A Blink
The objective of this lab is to use the timer peripheral to control the bliking rate of two LEDS and blink them at different rates. To do this I used two timers set at 12.5hz and 10hz. The first timer allows the first LED to blink at 12.5hz upon the interrupt and the second timer allows the second LED to blink a 10hz upon interrupt. 

## Processors Used
* MSP430G2553
* MSP430FR6989

## Changes in Code For Different Processors
The G2553 and the FR6989 have very similar code and are done with the same process, however they have different pin assignments which must be changed whens translating code from one board to the other. The other difference is that for the FR6989 you must disable the power-on default high impedence mode.

