# CODE QUALITY 

![CODEQUALITY_1](https://user-images.githubusercontent.com/101269445/164974473-1ac68d77-7635-41cd-8307-3692e1b5e18a.svg)
![CODEQUALITY_2](https://user-images.githubusercontent.com/101269445/164974507-c6ba6041-28d5-424b-93fb-5f324add5898.svg)
![CODEQUALITY_3](https://user-images.githubusercontent.com/101269445/164974510-fa6da620-a503-4ae8-a154-58ed7662cf06.svg)



# M2_Density_Based_Traffic_Light_System

# INTRODUCTION

Nowadays, controlling the traffic becomes major issue because of rapid increase in automobiles and also because of large time delays between traffic lights. So, in order to rectify this problem, we will go for density based traffic lights system. This article explains you how to control the traffic based on density.


In this system, we will use IR sensors to measure the traffic density. We have to arrange one IR sensor for each road; these sensors always sense the traffic on that particular road. All these sensors are interfaced to the microcontroller. Based on these sensors, controller detects the traffic and controls the traffic system.

# Principle

The main heart of this traffic system is microcontroller. IR sensors are connected to the PORT C (PC0, PC1, PC2, and PC3) of the microcontroller and traffic lights are connected to PORT B and PORT D. If there is a traffic on road then that particular sensor output becomes logic 0 otherwise logic 1. By receiving these IR sensor outputs, we have to write the program to control the traffic system.

If you receive logic 0 from any of these sensors, we have to give the green signal to that particular path and give red signal to all other paths. Here continuously we have to monitor the IR sensors to check for the traffic.

# Circuit Diagram

![Capture-compressed-1024x473](https://user-images.githubusercontent.com/101269445/164972284-3253a811-061b-4ee4-be4b-9d18ac063ecb.jpg)
