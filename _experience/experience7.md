---
title: Automated Pressure Sensor Testing System
subtitle: Professional
image: assets/img/experience/Pressure Sensor Test System.JPG
ImageCaption: Image provided only for illustration purposes.
alt: Automated Pressure Sensor Testing System

caption:
  title: Automated Pressure Sensor Testing System
  subtitle: Professional
  thumbnail: assets/img/experience/Pressure Sensor Test System.JPG
---
### Solution Description

This project designed to be used in a manufacturing fascility, to measure the force vs resistance response of for single point touch, finger electrodes. The electrodes that did not meet the required tolerances would be marked to be discarded.

The products were tested by pressing on them with a probe attached to a Z linear stage, that had an integrated load cell. While pressing on the product, the probe would also make contact with the UUT using spring loaded probes to measure the resistance. By doing so a force vs resistance curve could be measured for the full range of the product. The requirement was that each sensor must be measured in under 7s. The results were evaluated after all of the sensors were tested and a marker attached to a second Z linear stage would mark the faulty products.

A test run would begin by the operator loading in a casette, which contained more than a 100 sensors, entering test data and pressing start. The casette would then be pulled into the main test chamber, where an XY gantry would position the two Z stages. The whole system was enclosed and had an E-STOP circuit that would trip, whenever an operator would try to open one of the doors or panels, ensuring compliance with the safety standards in the UK.

The system was powered by a single cRIO that ran both the control code (real-time and FPGA) and the embedded UI. It was required to control a total of 5 motors, perform force and resistance readings, along with some digital IO for the safety circuitry, limit switches and other functions of the system.