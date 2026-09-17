# Nick's Modified RP-L FSR Code for DDR/ITG/SM5.1

<p>An open-source software package for DIY dance pads using RP-L thin-film pressure sensors and an ESP32 or Arduino.</p>

<p>This project is a modified version of existing FSR dance pad software, adapted for RP-L sensors and DIY DDR/ITG-style dance pads.</p>

> **WIP:** ESP32 code and setup guide are still being updated.

<img src="/img/rp-l 17.jpg" alt="17cm RP-L sensor" width="250" height="250">

## RP-L Sensors

<p>This project is designed around the <strong>RP-L</strong> thin-film pressure sensor.</p>

<p>No different from the <strong>Interlink 408</strong>, RP-L sensors have a trigger force of less than 20 g and a pressure range of 20 g to 10 kg+. Its main difference to the popular interlink FSRs are its response time of 10 ms, as opposed to the 408s 1ms.</p>

<p>The sensor is popular for Australian travel and homemade DDR/ITG pads, as interlink does not ship sensors to the AU</p>

<p><strong>More pressure → Lower resistance</strong></p>

<p>This makes it suitable for detecting steps and foot pressure in DIY dance pads.</p>

## Where to Buy

### Australia

- **Core Electronics** - RP-L-170 / DFRobot SEN0293
  - [Product Page](https://core-electronics.com.au/rp-l-170-thin-film-pressure-sensor.html)

- **Little Bird Electronics** - RP-L-170 / DF-SEN0293
  - [Product Page](https://littlebirdelectronics.com.au/products/rp-l-170-thin-film-pressure-sensor)

- **Pakronics** - RP-L-170 / DF-SEN0293
  - [Product Page](https://www.pakronics.com.au/products/rp-l-170-thin-film-pressure-sensor-df-sen0293)

### Manufacturer

- [**DFRobot**](https://www.dfrobot.com/product-1843.html)

>Prices and availability may change. Check the individual supplier before ordering.

## Features

- RP-L sensor support
- React web UI for configuration
- ESP32 support
- Arduino support
- USB HID keyboard output
- Individual sensor calibration
- Designed for DIY DDR homepads

## Requirements

### Hardware

- ESP32 or compatible Arduino board
- RP-L pressure sensors
- Resistors for the sensor voltage divider
- USB cable
- DIY dance pad hardware

### Software

- Python 3.6+
  - `virtualenv`
- Node.js 12+
  - `yarn`

<p>The Arduino/ESP32 firmware uses native USB HID keyboard functionality where supported.</p>

