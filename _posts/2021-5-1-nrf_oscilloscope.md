---
title: 'nRF5340 Oscilloscope Band'
date: May 2021
date_display: "May 2021"
featured_image: '/images/nrf.jpg'
excerpt: Measure and Analyse Voltages on the Go with nRF5340. A hand band to easy the process of measuring voltage and current of circuits.

---


## Motivation
Almost all Hobbyist and Makers dream about owning a Oscilloscope but due to huge prices we could not afford it. So why not make your own?

I have created a Hand Held Oscilloscope which can be used as a wearable to measure voltages with probes attached to your fingers.

## Software:

* First I had setup the nRF5340 with Zephyr OS and all its dependencies like west.
* Then Installed the nRF Toolchain.
* Then tested out sample code for blinky and ncs-display.
* Then worked on reading values from Potentiometer and PWM Signals generated from Arduino

## Hardware and Build

The Main Parts were the Body Case and Wiring the Cables

* The Body was 3D Printed and Sketched by me using Fusion360, Here is the STL Files
* Then the Jumper Cables were Attached to nRF5340 by soldering Headers to Remaining Analog and Ground Pins as All header pins were occupied by Display Shield.
* To use it as a Wearable, I have added place for adding Flaps on both sides of 3D Printed Case
* And to use with Fingers I have Printed Finger Holders

## Future Work
There are many improvements I am adding to it

* Adding Voltage StepDown Circuit to support greater voltages
* Adding Current Sensing by using Shunt Resistor Method
* Creating a GUI with touch for switching between features and voltages.

[Github Repo]()

[Fina Report]()
