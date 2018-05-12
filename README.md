# LightPadControl
Arduino control controlling Artograph light pads for automatic screening. Push the switch for one light pad to the "ON" configuration to begin the "window screen" protocol.

# CONTENTS:

### Gerber files
- These contain the Gerber files needed to generate the PCB connecting the parts together. Uses 12 1kOhm resistors, 12 10kOhm resistors, 12 NPN transistors, 12 switches, an Arduino ATMEGA256, and one female barrel connector. The Arduino should run the code in the other folder. The barrel connector should be connected to an 18 V power source.

### Arduino code
- Runs two window experiments, the durations and time of which are settable using the constant ints at the top of the code.
