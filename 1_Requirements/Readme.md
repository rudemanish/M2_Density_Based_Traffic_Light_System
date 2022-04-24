# INTRODUCTION

Nowadays, controlling the traffic becomes major issue because of rapid increase in automobiles and also because of large time delays between traffic lights. So, in order to rectify this problem, we will go for density based traffic lights system. This article explains you how to control the traffic based on density.


In this system, we will use IR sensors to measure the traffic density. We have to arrange one IR sensor for each road; these sensors always sense the traffic on that particular road. All these sensors are interfaced to the microcontroller. Based on these sensors, controller detects the traffic and controls the traffic system.

# Principle

The main heart of this traffic system is microcontroller. IR sensors are connected to the PORT C (PC0, PC1, PC2, and PC3) of the microcontroller and traffic lights are connected to PORT B and PORT D. If there is a traffic on road then that particular sensor output becomes logic 0 otherwise logic 1. By receiving these IR sensor outputs, we have to write the program to control the traffic system.

If you receive logic 0 from any of these sensors, we have to give the green signal to that particular path and give red signal to all other paths. Here continuously we have to monitor the IR sensors to check for the traffic.

# BASIC COMPONENTS OF A CAR TEMPERATURE CONTROL
## HARDWARE

### Circuit Components:

1) ATmega8 controller

2) PCB board

3) IR sensors -4

4) LED’s-12(4-red,4-green,4-yellow)

5) 12v Battery or adaptor

6) Serial cable

7) Connecting wires


# SOFTWARE

MICROCHIP STUDIO

VS CODE

SIMULIDE

# BASIC COMPONENTS OF A CAR TEMPERATURE CONTROL

## COMPONENTS

ATmega 328 :-

![ATmega328(1)](https://user-images.githubusercontent.com/101269445/164972991-e5818234-c3e5-46f8-97a2-e081de06cec3.jpg)


ATmega328 is commonly used in many projects and autonomous systems where a simple, low-powered, low-cost micro-controller is needed.The Atmel 8-bit AVR RISC-based microcontroller combines 32 KB ISP flash memory with read-while-write capabilities, 1 KB EEPROM, 2 KB SRAM, 23 general-purpose I/O lines, 32 general- purpose working registers, 3 flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a byte-oriented 2-wire serial interface, SPI serial port, 6-channel 10-bit A/D converter (8 channels in TQFP and QFN/MLF packages), programmable watchdog timer with internal oscillator, and 5 software- selectable power-saving modes. The device operates between 1.8 and 5.5 volts. The device achieves throughput approaching 1 MIPS/MHz.
