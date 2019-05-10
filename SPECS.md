# SPECIFICATIONS
One channel RF micro switch

## Table of contents
* [Description](#description)
* [Specifications](#specifications)
* [Features](#features)
* [Additional notes](#additional-notes)

## Description
Module for receiving a 433MHz RF signal from a settable remote control. The signal causes the activation of an output.

This module is based on SYN480R and RFE272A. The choice of these components allows a good integration and the number of external components is extremely limited. 

## Specifications

* Voltage: 3.5V-12V
* Ampere: max 1mA
* Outputs: 1
* Package: any SMD
* Form factor: smallest form factor
* Work frequency: 433MHz
* Encoding: PT2262

## Features

The SYN480R is a single chip ASK/OOK (ON-OFF Keyed) RF receiver IC. This device is a true “antenna-in to data-out” monolithic device. All RF and IF tuning are accomplished automatically within the IC which eliminates manual tuning and reduces production costs. The result is a highly reliable yet low cost solution.

The SYN470R is a fully featured part in 16-pin packaging, the SYN480R is the same part packaged in 8-pin packaging with a reduced feature set.The SYN480R is equivalent to the SYN470N, however SYN480R has a smaller form (SO-8 instead of SO-16), although it allows a minor control of the settings, however sufficient for the application.

Relevant features of the SYN480R integrated circuit:
* Frequency range from 300 MHz to 440 MHz
* High receiver sensitivity: -106dBm (315MHz), -107dBm (433MHz)
* Reduced energy consumption
* Highly integrated with an extremely low external number of pieces

Relevant features of the RFE272A integrated circuit:
* Compatible with most coding chips or fixed code such as PT2262, PT2260, SC2260, EV1527, SC1527, HS1527, RT1527, etc ...
* Intelligent recognition technology, secure identification by the type of encoding chip.
* Intelligent learning without manual coding.
* Supports 4bit data code output
* Supports up to 40 remote controls
* 1.8-5.5V working voltage
* Micropower current: <0.8mA
* Pacage: SO-8

A 5V voltage stabilizer and an N-type MOSFET for driving the output load are also used


## Additional notes

* https://cdn-shop.adafruit.com/datasheets/PT2262.pdf
* http://uploadpdf.ic37.com/RFE/RFE273_datasheet_1232987/200982/RFE273_datasheet.pdf
* https://www.ebuy7.com/item/wireless-remote-control-decoder-chip-ev1527-decoder-chip-rfe272a-instead-of-pt2272-tdh6300-554751504558

* https://docs-emea.rs-online.com/webdocs/13d1/0900766b813d1afb.pdf