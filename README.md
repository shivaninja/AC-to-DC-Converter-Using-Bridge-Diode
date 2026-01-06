
# PCB Design AC to DC converter Using Bridge Diodes/ Rectifiers

This project is about a PCB development of AC to DC circuit using Bridge Diodes or Rectifier.
This Project uses KICAD with Schematics, Footprint Layouts , PCB Layout.

# Software Used:
KiCAD

# Files Included
1. Schematics
2. Footprint Inlcude Libraries Files
3. Gerber Files

# Components Used
1. Diodes 4x
2. LED 1x
3. Capacitor(Electrolytic) 1x
4. Resistor 2x (1: 10K ohm for Discharging of Capacitor, 2: 2.2K ohm for LED)
5. Screw Terminal 2x

# Why Capacitor is used
After the bridge rectifier, the output is NOT smooth DC.

AC → goes up and down

Diodes flip the negative part up

Result = bumps, not flat voltage

To prevent bumps and fluctuating voltages and achieve capacitor is used.

Capicator is like a small water tank with pipe at its roof. The water will not come out untill the whole tank is filled. 

In this way the voltage is discharged with stability and slowly

# Capacitor 

Capacitor is like a temporary battery

It Stores energy when voltage goes up

Gives back energy when voltage goes down


## What happens WITH the 10 kΩ resistor?

Power ON → capacitor fills normally

Power OFF → charge flows through the resistor and Resistor consumes all the voltage untill it becomes zero

Voltage slowly goes to zero 

capicitor Discharges only when Voltage is zero

Circuit becomes safe and predictable

The resistor is a controlled leak.

## What happens WITHOUT the 10 kΩ resistor?

Power ON → capacitor fills up (voltage rises)

Power OFF & There is no 10k ohm resistor to consume the voltage

The voltage does not become zero

Since the voltage does not become zero the capacitor does not discharge(NOTE: Capicitor only discharges when voltage becomes zero)

Capacitor stays charged for a long time

You touch the circuit →  small shock / spark possible

Multimeter still shows voltage → confusing

The “tank” stays full because there is no leak.

# NOTE: 
All the Details related to files are included in folder
