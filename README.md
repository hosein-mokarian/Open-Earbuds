# Open Earbuds

It is a free and open source project in which an earbuds is implemented. Earbuds are most useful electronic gadgets nowadays. Older versions used wires to transfer sound data, but newer versions use a wireless communication. Bluetooth Low Energy (BLE) is the used wireless communication. It is really suitable for sound streaming. From an electronic engineer's view, it is really hard to design a small, low power and battery operated device which can be used inside ears. It has lots of challenges. This project is a guide for ones who want to know the basics of Earbuds.

#### Design Features

- Bluetooth Low Energy
- Low power, battery operated device
- Chip antenna
- Matching network design
- MEMS sensors
- Audio codecs ICs
- Audio power amplifier
- Power IC management
- Battery charging through Power Line Communication (PLC)



#### Featured Applications

- Earbuds
- Hearable
- Audio streaming
- Voice Recognition



#### Block Diagram

Fig.1 shows the overall view of the design. 

![Block Diagram](https://github.com/hosein-mokarian/Open-Earbuds/blob/main/Fig/open_earbuds_block_diagram.jpg?raw=true)

<div style="text-align: center;">
    <p>Fig 1. Block Diagram</p>
</div>




#### Board Images

3D images of all boards are shown in Fig.2.



#### Key System Specifications

- Low profile
- Low power
- The Bluetooth communication
- Support audio codecs



#### Introduction

Earbuds are the most innovative electronic device, because they have lots of amazing features such as: low profile, low power and art design. Earbuds design has lots of challenges. The design has both electronic and mechanical aspects. It must be small enough to put inside ears easily and also it should have nice view. Because it uses battery, being low power is really important. Beside, the board space is too low. So, low profile low power component selection is really important. For wireless communication, the BLE should be used. It is convenient and all phones support it. BLE antenna design is a big challenge. Chip antenna and antenna on PCB is the two possible ways. Because of limited space, chip antenna is better. 



#### System Description



#### Block Diagram

The device consists of different parts:

- Low Power BLE MCU
- Audio Codec IC
- Audio Power Amplifier
- Power management IC
- Chip Antenna
- Matching Network
- Battery Charger
- Capacitive Touch Sensors
- MEMS Speaker
- MEMS Microphone

All of them will be discussed in the following.



###### MCU

Wireless series of STM32 microcontroller is selected as the core of the system. It has some interesting features:

- RF transceiver supporting Bluetooth® 5.3 specification
  - Dedicated Arm® 32-bit Cortex® M0+ CPU for real-time Radio layer
- ARM Cortex M4
  - Frequency up to 64 MHz
- 64 Pins / 1 MB Flash / 256 KB RAM
- I2C / SPI / SAI
- Touch sensing controller (TSC)
- Ultra-low-power
  - 1.71 to 3.6 V power supply



###### Antenna

Two ways are available for BLE antenna design: PCB antenna and chip antenna. The PCB antenna is low cost and some convenient patterns can be found in ST documentations. However, it needs more space than chip antenna. Being low profile is one of main aspect of earbuds. So, chip antenna is a better selection   for our purpose. Here is some features of selected chip antenna:

![Chip Antenna](https://github.com/hosein-mokarian/Open-Earbuds/blob/main/Fig/nn01-101.PNG?raw=true)

- NANO mXTEND (NN02-101)
- Datasheet
- Smallest clearance
  - 5mm x 5mm
- Miniature
- Smallest Virtual Antenna™ form factor of 3.0 mm x 2.0 mm x 0.8 mm
  - Dimensions (L x W x H): 3.0 mm x 2.0 mm x 0.8 mm
- Bluetooth and Wi-Fi (2400 – 2500MHz)
- Impedance: 50 Ohms



###### Audio codec

###### MEMS speaker

The MEMS speakers from the Ganymede series are ideal for creating modern earphones and headphone designs as well as wearables such as audio glasses and AR/VR glasses. Its features is listed as below: 

![MEMS Speaker](https://github.com/hosein-mokarian/Open-Earbuds/blob/main/Fig/Ganymede-Perspective-Top-Transparent.png?raw=true)

- ACHELOUS UT-P2020
- Datasheet
- Resonance frequency: 2.7 kHz
- Capacity: 27±5 nF
- Maximum AC voltage (peak) – up to 20 kHz: 15VP
- Maximum DC voltage:15V
- Size [mm]: 6.7 x 4.7 x 1.58



###### MEMS microphone

The MP34DT06J is an ultra-compact, low-power, omnidirectional, digital MEMS microphone built with a capacitive sensing element and an IC interface.

- MEMS audio sensor omnidirectional digital microphone
- MP34DT06J
- Features
  - Single supply voltage
  - Low power consumption
  - Omnidirectional sensitivity
  - PDM output

- Supply voltage
  - Min: 1.6  Typ: 1.8 Max: 3.6 V
- Current consumption in normal mode: 650 μA
- Current consumption in power-down mode: 5 μA
  - power-down mode: *Input* *clock in static* *mode*
- Capacitive load: 100 pF
- fCLK Clock frequency for normal mode 
  - Min: 1.2 MHz Max: 3.25 MHz



###### Battery charger

###### Power management



#### System Design Theory

#### Simulation

#### Schematics

All schematics are in PCB folder.

#### Bill of Materials

The list of used electronic components can be found in BOM folder.

#### PCB Layout

All PCB files are in PCB folder.

#### Altium Project

#### Layout Guidelines

#### Test Setup

#### Test Data



#### References

- Earbuds
  - https://cad.onshape.com/documents/d1d05b75101383c1321eefd4/w/1353c84e3d4b409c38caf0c8/e/21b60902b6faeb998629c7ea?renderMode=0&uiState=65fc2b8b0256376153797aea
- Charging Case
  - https://cad.onshape.com/documents/4bb8c5e7fc47f1b2d4e7f729/w/f99f51ebe60cb272729c223f/e/9bf1601e2016c3cb66cb5705?renderMode=1&uiState=65fc2bf8cb9cb5171ff44d34



