# Supermileage Altium Tutorial

## Introduction

In this tutorial you will develop a circuit to flash an LED using the NE555P timer IC from Texas Instruments.

The 555 timer IC is an integrated circuit used in a variety of timer, pulse generation and oscillator applications. Designed in 1972 the 555 has become one of the worlds most iconic chips with an estimated 1 billion units sold every year. The chip is composed of two comparators, a transistor, a SR flip-flop, a push pull output driver and a voltage divider. Although we could design our own NE555 timer using these building blocks in Altium it is much easier to purchase the IC and create a schematic symbol for it instead.

## Task

To start create a new project in Altium and name it ELEC-DEM-555Timer. Be sure to place it within the repository project folder. The project will also require the creation of one schematic document as well as one schematic library.

The goals of the project are as follows.
* Create a library containing all the parts needed to make the circuit
  - Be sure to label the pins Display Names with their actual names (you will need to find the datasheet)
* Link the components to our supplier Digikey
* Create the schematic
  -  label known nets (Vcc and Gnd)
* Export the BOM as a .csv

<p align="center"><img src="figures/555timer.png" width="50%" height="50%" title="555 Circuit"></p>

Dont forget to commit and push the project once you are done!
