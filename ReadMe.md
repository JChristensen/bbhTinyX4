# ATtinyX4 Breadboard Helper #
http://github.com/JChristensen/bbhTinyX4  
ReadMe file  
Jack Christensen Jan 2015  

## Introduction ##

The Breadboard Helper is the easiest way to breadboard an ATtiny24/44/84! This small board (1.2 in. x 1.3 in.) contains everything needed to run an ATtinyX4 microcontroller, including:
- ICSP header
- Filter and bypass capacitors
- Reset button with pullup resistor
- LED with current-limiting resistor

The Breadboard Helper breaks out all the MCU's pins to a 12-pin header and also connects to the breadboard's power rails. Plug the Breadboard Helper into a breadboard, add power, connect a programmer, and the microcontroller is ready to go!

PC boards can be ordered [from OSH Park](https://www.oshpark.com/shared_projects/I1Z984Pi).  
A Bill of Materials with Mouser part numbers is part of this repo.

## Power Connection ##

A two-pin header connects the Breadboard Helper to the breadboard's power rails. This header should be soldered ***either*** into the position labeled **"a"** ***or*** into the position labeled **"b"**.

Use position **"a"** for breadboards where the power rail holes line up with those in the main part of the breadboard (most full-size breadboards). Use position **"b"** for breadboards where the power rail holes are staggered between those in the main part of the breadboard (most half-size breadboards).

Observe polarity carefully and ***do not*** solder headers into both positions **"a"** and **"b"**, as the result will likely not fit into any breadboard!

## Arduino Pin Mapping ##

The 12-pin header is labeled with Arduino pin numbers 0-10 plus RESET, using the pin mapping from the [Arduino-Tiny core](https://code.google.com/p/arduino-tiny/). Other cores may be used with the Breadboard Helper but be aware that the pin mapping may be different. The AVR port and pin numbers are also labeled for easy reference.

The LED is connected to Arduino pin 6 or PA4 (ADC4/USCK/SCL/T1/PCINT4).

## CC BY-SA ##
"ATtinyX4 Breadboard Helper" by Jack Christensen is licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).

![](photo link)
  
