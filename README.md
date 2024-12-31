# Motor Tester - STM32IDE

## Introduction[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)

The goal of this STM23IDE project is to implement a motor tester. Motor testers are useful for determining servo motor range, continuous rotation motor speed, prototype testing, and centering servos. Here, a potentiometer value is inputted from 0 to 3.3V and convert it to a PWM signal to control a motor. The potentiometer is connected to an external ADC chip which sends data to the MCU over SPI. <a href="https://uwarg-docs.atlassian.net/wiki/spaces/BOOT/pages/1998061593/Challenge">Read more</a></p>

---

## Design[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#design)

![Motor Tester Overview](https://github.com/user-attachments/assets/b1ed46c9-fb3b-4f85-88c5-133279ec86d2)

---
<div align="right">[ <a href="#introduction">↑ Back to top ↑</a> ]</div>
