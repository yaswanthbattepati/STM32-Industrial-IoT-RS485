# STM32-Industrial-IoT-RS485
STM32-based Industrial IoT monitoring system using RS485 communication, sensor monitoring, I2C LCD, UART, interrupts, and real-time fault status indication.
# STM32-Based Industrial IoT Monitoring System

An ARM-based Industrial IoT monitoring system developed using STM32 microcontrollers and RS485 communication.

## Features

- Real-time sensor monitoring
- 12-bit ADC-based sensor acquisition
- NORMAL, WARNING, and ALERT state classification
- I2C LCD display
- LED-based status indication
- Push-button interrupt handling
- UART-based RS485 communication
- Sensor Node and Monitor Node architecture
- Real-time data transmission between two STM32 nodes

## Hardware

- STM32 Nucleo L031K6 × 2
- MAX485 × 2
- Potentiometer
- 16×2 I2C LCD × 2
- Green LED
- Yellow LED
- Red LED
- Pushbutton
- 220Ω resistors

## Communication

The Sensor Node reads the sensor value and transmits:

ADC value  
Sensor level percentage  
System state

through an RS485 communication bus to the Monitor Node.

## Software

- Embedded C/C++
- Arduino STM32 Core
- Wokwi
- I2C
- UART
- RS485
- GPIO
- Interrupts
- ADC

## System Architecture

Sensor → STM32 Sensor Node → MAX485 → RS485 Bus → MAX485 → STM32 Monitor Node → LCD/LED

## Simulation

The complete circuit is simulated in Wokwi.

## Author

Yaswanth Battepati
