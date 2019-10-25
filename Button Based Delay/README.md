# Button Based Delay


## Processors Used
* MSP430G2553
* MSP430FR6989

## Changes In Code For Different Processor
The G2553 and the FR6989 have very similar code and are done with the same process, however they have different pin assignments which must be changed whens translating code from one board to the other. The other difference is that for the FR6989 you must disable the power-on default high impedence mode.
