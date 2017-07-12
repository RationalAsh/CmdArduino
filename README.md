## commandProcessor (originally CmdArduino by Akiba at Freaklabs.org)

Modified by Ashwin Narayan

## Modified version

The modified version of the library has been updated to C++ and features a slightly
modified set of functions. It should also work with the Teensy development boards.

## TODO:
 * Update examples
 * Test on non-teensy boards



## Original README text
---

The Arduino Command Line Interface, aka CmdArduino, is a simple shell that can
be run on an Arduino. It's nothing fancy and its main purpose is to allow users
to easily call their functions on a running Arduino via a simple serial
terminal. It also allows users to pass in arguments from the command line into
the functions they wrote so they can easily toggle pins, set blinking speed,
set pwm duty cycles, or whatever else might need command line user input. Using
it is fairly simple and just requires unzipping the files into the
"Arduino/libraries" sub-directory in the Arduino program folder.
