# TinCAN-RP2040-CAN-Simulator-Bench

### What does "TinCAN" do?
  This project allows you to boot modules from modern vehicles such as the SYNC 3 and SYNC 4 modules on a "bench". This is done by simulating the canbus network of the vehicle using an inexpensive($20-30) RP2040 Canbus Board.

### What's the point?
  At the time there is no existing project to power/boot SYNC 4 models and/or newer(2020+) modules. There also isn't a compact user friendly option to do so.
## [Purchase Kit, Harness's, or Parts Here](https://www.adafruit.com/product/4739)
![Screenshot](docs/images/TinCAN.png)


## Hardware List (Required)
  - Adafruit RP2040 Canbus Board [Adafruit_RP2040CAN](https://www.adafruit.com/product/5724) , [Mouser_RP2040CAN](https://mou.sr/3xuF0uN)
  - Adafruit MPM3610 21V -> 5V [Adafruit_MPM3610](https://www.adafruit.com/product/4739) , [Mouser_MPM3610](https://mou.sr/3Vck6YR)
  - Molex 6P Connector [Mouser_Molex6P](https://mou.sr/3JtCprp)
  - Barrel Jack [Mouser_BarrelJack](https://www.google.com)
  - CASE... 3D Print or CNC Aluminum [3D Print](https://github.com/Anrew3/TinCAN-RP2040-CAN-Simulator-Bench/hardware/enclosure/Carry_Tray_RP2040.3mf) , [CNC Aluminum](https://www.google.com)
  - M2 & M4 Screws (4x M4x.7mmx15mm, 5x M2x.7mmx5mm)

## Hardware List (Optional)
  - JST Headers [Mouser_RP2040CAN](https://www.google.com)
  - ESP32 WIFI Addon [Mouser_MPM3610](https://www.google.com)

## Wiring (TINCAN)
![Screenshot](docs/images/TinCAN_Wiring.jpg)

## Flashing Firmware

Use this site to flash the firmware via USB once the device is built. If you have issues you can use the Arduino IDE as well to build & upload manually.

<div align="center">
  <a href="https://anrew3.github.io/TinCAN-RP2040-CAN-Simulator/tincan-flasher.html"
     target="_blank"
     rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/🔧%20Flash%20Firmware-Open%20Flasher-blue?style=for-the-badge&logo=browser&logoColor=white"
         alt="Open TinCAN Flasher">
  </a>
</div>
