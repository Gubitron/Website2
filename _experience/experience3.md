---
title: Datalogging System for Testing Wind Turbines
subtitle: Professional
image: assets/img/experience/Wind Turbine Test System.JPG
ImageCaption: Image provided only for illustration purposes.
alt: Datalogging System for Testing Wind Turbines

caption:
  title: Datalogging System for Testing Wind Turbines
  subtitle: Professional
  thumbnail: assets/img/experience/Wind Turbine Test System.JPG
---
### Solution Description

The system was designed to be used as a data logging center for testing and characterising wind turbines. Every few months a new wind turbine would arrive, that could be much smaller or bigger than the previous one, would have greatly different measurement requirements, would likely be made by a different manufacturer and therefore would have different interfacing requirements.

<br>Because the wind turbines under test could be so different, the system was designed to be highly reconfigurable, so that more or different measurement devices could be added with minimal effort. To achieve this National Instruments hardware was used, which on average included:
1. 5 PXI chassis
1. 3 cDAQ chassis
1. A reflective memory module
1. Some type of PLC or similar device for interfacing with the turbine

<br>While the PXI chassis were mainly used for outside signals, such as, voltage, current, velocity, force and similar measurements, the cDAQ chassis would measure similar signals, but would be located inside the nacelle of the turbine, due to their ruggedness. The reflective memory module was used to allow the data logging system to communicate with other systems that were involved in controlling and testing the wind turbine. Typically, the system would be logging 1000 to 1700 individual signals, sampled anywhere from 200 Hz up to 100kHz. Due to large amounts of data being logged, that system would regularly fill up a 40TB+ of space. The data was also synchronised to at least microsecond accuracy, while the data acquisition equipment was scattered across the whole building.

<br>Such a solution allowed our customers to complete many trials for many different wind turbines, while keeping the setup time for each new turbine to a minimum.