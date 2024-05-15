![Screen Shot 2024-05-07 at 7 39 55 PM](https://github.com/Project-Nibbler/Project-Nibbler/assets/43685920/a28b5fc4-33dd-41cb-9eb1-91ef7dac5f9e)
# Project Nibbler
Open source pick and place object assembler add-on to the Ender 5 pro 3D printer.  
https://research.avenues.org/moonshots/project-nibbler/
## Introduction 
Nibbler is a pick-and-place add-on to the Ender 5 pro that can build and assemble 3D objects from building block "pucks". 

This repository contains everything needed to set up a Nibbler machine from scratch. 
## Project Status
This repository represents the culmination of four years of work on Project Nibbler done by four generations of Avenues students from Sao Paolo, Brazil and New York, USA.

## Ender 5 pro setup
The Nibbler pick and place machine is an add-on to the Ender 5 Pro. The following modifications must be made to a stock Ender 5: 
 
The Creality Ender 5 Pro is the 3D Printer base that we are hacking and customizing to be able to print with nibbles and binder matrix.
* Build Volume: 220mm x 220mm x 300mm (8.7" x 8.7" x 11.8")
* Frame: Aluminum
* Kinematics: Cartesian XY-head
* Bed leveling: Manual

## UV Light System

## Suction

## Puck Dispenser

The puck dispenser is a contraption that holds up to a hundred pucks. It dispenses pucks one at a time, in a flat orientation, for the suction nozzle to pick up. The puck dispenser encorperates a windmill roller design, which stirs pucks inside, and forces it down a chute. This orients the puck correctly.

### Assembly Instructions

The puck dispenser features a thin profile NEMA 17 stepper motor and a coupler. 

1. Buy a thin profile NEMA 17 stepper motor, 5mm coupler, and a m3 screw hardware pack.
2. Download and 3D print the base and hopper in PLA or similar material.
3. Download and 3D print the roller in TPU (preferably with 40A shore hardness).
4. Screw the motor to the base.
5. Put the coupler onto the motor shaft.
6. Screw the hopper to the base.
7. Insert the roller, use a lot of force.
8. Screw in the coupler set screws.
9. Voila! You are finished.

### CAD File
[Onshape CAD file of the puck dispenser](https://cad.onshape.com/documents/25d72b5aafd87145113655bb/w/c10e9e672a361535dbc8285c/e/5a3a8ab8565b4f63dfe7123e?renderMode=0&uiState=6643fa2824a2832b766e41b9)

The CAD document is export-enabled, which means that you are welcome to download the file and make changes. The main file is "Assembly 2". 


## Resin
Currently, resin is injected into the resin container manually every 10 minutes. The puck is dipped into the resin and cured onto the build plate. An additional customization option is creating an automatic resin dispenser with a motor actuator connected to a long tube. 
## Slicer (Code)


