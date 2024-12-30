# Embedded-Bootcamp

## Welcome to the WARG Firmware Bootcamp! 

Full instructions can be found on the [Bootcamp Confluence Page](https://uwarg-docs.atlassian.net/wiki/spaces/BOOT/pages/1997373445/2021+Firmware+Bootcamp).

This repository contains a basic STM32IDE project that will be modified to complete the bootcamp.

For git specific questions and direction please visit our [Git Tutorial](https://uwarg-docs.atlassian.net/wiki/spaces/TUT/pages/1544257554/Git+and+GitHub+Tutorial).


## Introduction[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)

The goal of this STM23IDE project is to implement a motor tester. Motor testers are useful for determining servo motor range, continuous rotation motor speed, prototype testing, and centering servos. Here, a potentiometer value is inputted from 0 to 3.3V and convert it to a PWM signal to control a motor. The potentiometer is connected to an external ADC chip which sends data to the MCU over SPI. <a href="https://uwarg-docs.atlassian.net/wiki/spaces/BOOT/pages/1997373445/2021+Firmware+Bootcamp">Read more</a></p>

---

## Design[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#design)

![Motor Tester Overview](https://github.com/user-attachments/assets/b1ed46c9-fb3b-4f85-88c5-133279ec86d2)

---
<div align="right">[ <a href="#introduction">↑ Back to top ↑</a> ]</div>
