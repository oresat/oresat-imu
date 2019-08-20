---
title: IMU and Magnetometer
layout: default
nav_data:
  - name: ADCS
    link: /github_pages/ADCS/
    repo: /oresat-acs-board
    defcolor: red
---
# oresat-imu
OreSat's IMU + Magnetometer board

CAN address: 0xh41

The IMU on the LV2 flight computer is the [ADIS16405](http://www.analog.com/en/products/sensors/inertial-measurement-units/adis16405.html#product-overview). The IMU contains a triaxial gyroscope, triaxial accelerometer, and an embedded temperature sensor. These parameters are output from the IMU via SPI, and will need to be sent to the CAN bus using an [STM32F042K6](http://www.st.com/content/st_com/en/products/microcontrollers/stm32-32-bit-arm-cortex-mcus/stm32f0-series/stm32f0x2/stm32f042k6.html) mcu or other M0 controller. 

