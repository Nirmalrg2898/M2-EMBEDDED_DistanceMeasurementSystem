# M2-EMBEDDED_DistanceMeasurementSystem

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/b19dcede954c42da9623770a634df37b)](https://www.codacy.com/gh/Nirmalrg2898/M2-EMBEDDED_DistanceMeasurementSystem/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Nirmalrg2898/M2-EMBEDDED_DistanceMeasurementSystem&amp;utm_campaign=Badge_Grade)|
[![Cppcheck](https://github.com/Nirmalrg2898/M2-EMBEDDED_DistanceMeasurementSystem/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/Nirmalrg2898/M2-EMBEDDED_DistanceMeasurementSystem/actions/workflows/cppcheck.yml)|
[![Build](https://github.com/Nirmalrg2898/M2-EMBEDDED_DistanceMeasurementSystem/actions/workflows/compile.yml/badge.svg)](https://github.com/Nirmalrg2898/M2-EMBEDDED_DistanceMeasurementSystem/actions/workflows/compile.yml)


## Introduction

#####  This circuit is developed by interfacing ultrasonic sensor“HC-SR04” with AVR microcontroller. This sensor uses a technique called “ECHO” which is something you get when sound reflects back after striking with a surface. We know that sound vibrations can not penetrate through solids. So what happens is, when a source of sound generates vibrations they travel through air at a speed of 220 meters per second. These vibrations when they meet our ear we describe them as sound. As said earlier these vibrations can not go through solid, so when they strike with a surface like wall, they are reflected back at the same speed to the source, which is called echo. Ultrasonic sensor “HC-SR04” provides an output signal proportional to distance based on the echo. The sensor here generates a sound vibration in ultrasonic range upon giving a trigger, after that it waits for the sound vibration to return. Now based on the parameters, sound speed (220m/s) and time taken for the echo to reach the source, it provides output pulse proportional to distance.

## Components Required
##### Hardware: ATmega328, Power supply (5v), LCD hd_44780_E, 1000uF capacitor, 10KΩ resistor (2 pieces) , HC-SR04 sensor.
##### Software: Simulide, Visual Studios.

## Folder Structure
Folder               | Description
-------------------  | -----------------------------------------
`1_Requirements`     | Documents Detailing requirements and research.
`2_Design_diagram`     | Documents Specifying design details.
`3_Implementation`   | All Code and Documentation.
`4_TestPlan`| Test Cases.

