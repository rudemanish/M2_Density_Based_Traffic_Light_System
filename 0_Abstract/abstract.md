# ABSRACT :-

Nowadays, controlling the traffic becomes major issue because of rapid increase in automobiles and also because of large time delays between traffic lights. So, in order to rectify this problem, we will go for density based traffic lights system. This article explains you how to control the traffic based on density.In this system, we will use IR sensors to measure the traffic density. We have to arrange one IR sensor for each road; these sensors always sense the traffic on that particular road. All these sensors are interfaced to the microcontroller. Based on these sensors, controller detects the traffic and controls the traffic system.In present, vehicular traffic is increasing throughout the world, especially in large urban areas. As the number of road user's increase constantly and current resources & infrastructures being limited; a smart traffic control will become a very important issue in the future. These needs have led to an ever increasing demand for an " intelligent " traffic control system. Therefore, optimization of traffic control to better accommodate this increasing demand is needed. Our project will demonstrate the optimization of traffic lights in a city using wireless sensors. Traffic light optimization is a tough problem. With multiple junctions, the complexity increases as the state of one light node influences the flow of traffic towards many other nodes. We proposed a traffic light controller that allows us to control and study different situations of traffic density. We sense the density of traffic using infra-red sensors. The key role behind the implementation of the " Traffic density based light control system " is to make use of an ATMEGA328 controller which performs processing of the real time data provided by the infra-red sensors, eventually controlling the traffic flow via the LED traffic lights.

## Principle :-
The main heart of this traffic system is microcontroller. IR sensors are connected to the PORT C (PC0, PC1, PC2, and PC3) of the microcontroller and traffic lights are connected to PORT B and PORT D. If there is a traffic on road then that particular sensor output becomes logic 0 otherwise logic 1. By receiving these IR sensor outputs, we have to write the program to control the traffic system.

If you receive logic 0 from any of these sensors, we have to give the green signal to that particular path and give red signal to all other paths. Here continuously we have to monitor the IR sensors to check for the traffic.

# BASIC COMPONENTS OF A Density Based Traffic System

## HARDWARE

## Circuit Components:

ATmega8 controller

PCB board

IR sensors -4

LED’s-12(4-red,4-green,4-yellow)

12v Battery or adaptor

Serial cable

Connecting wires

## SOFTWARE

MICROCHIP STUDIO

VS CODE

SIMULIDE

# BASIC COMPONENTS OF A Density Based Traffic System

## COMPONENTS

ATmega 328 :-

ATmega328(1)

ATmega328 is commonly used in many projects and autonomous systems where a simple, low-powered, low-cost micro-controller is needed.The Atmel 8-bit AVR RISC-based microcontroller combines 32 KB ISP flash memory with read-while-write capabilities, 1 KB EEPROM, 2 KB SRAM, 23 general-purpose I/O lines, 32 general- purpose working registers, 3 flexible timer/counters with compare modes, internal and external interrupts, serial programmable USART, a byte-oriented 2-wire serial interface, SPI serial port, 6-channel 10-bit A/D converter (8 channels in TQFP and QFN/MLF packages), programmable watchdog timer with internal oscillator, and 5 software- selectable power-saving modes. The device operates between 1.8 and 5.5 volts. The device achieves throughput approaching 1 MIPS/MHz.

IR SENSOR :-
IR-Sensor

An infrared sensor is an electronic device, that emits in order to sense some aspects of the surroundings. An IR sensor can measure the heat of an object as well as detects the motion. These types of sensors measure only infrared radiation, rather than emitting it that is called a passive IR sensor. Usually, in the infrared spectrum, all the objects radiate some form of thermal radiation. These types of radiations are invisible to our eyes, which can be detected by an infrared sensor. The emitter is simply an IR LED (Light Emitting Diode) and the detector is simply an IR photodiode that is sensitive to IR light of the same wavelength as that emitted by the IR LED. When IR light falls on the photodiode, the resistances and the output voltages will change in proportion to the magnitude of the IR light received.

LED :-
led2

A light-emitting diode (LED) is a semiconductor device that emits light when an electric current flows through it. When current passes through an LED, the electrons recombine with holes emitting light in the process. LEDs allow the current to flow in the forward direction and blocks the current in the reverse direction.Light-emitting diodes are heavily doped p-n junctions. Based on the semiconductor material used and the amount of doping, an LED will emit a coloured light at a particular spectral wavelength when forward biased. As shown in the figure, an LED is encapsulated with a transparent cover so that emitted light can come out.
