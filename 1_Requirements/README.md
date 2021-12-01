## Introduction

#####  This circuit is developed by interfacing ultrasonic sensor“HC-SR04” with AVR microcontroller. This sensor uses a technique called “ECHO” which is something you get when sound reflects back after striking with a surface. We know that sound vibrations can not penetrate through solids. So what happens is, when a source of sound generates vibrations they travel through air at a speed of 220 meters per second. These vibrations when they meet our ear we describe them as sound. As said earlier these vibrations can not go through solid, so when they strike with a surface like wall, they are reflected back at the same speed to the source, which is called echo. Ultrasonic sensor “HC-SR04” provides an output signal proportional to distance based on the echo. The sensor here generates a sound vibration in ultrasonic range upon giving a trigger, after that it waits for the sound vibration to return. Now based on the parameters, sound speed (220m/s) and time taken for the echo to reach the source, it provides output pulse proportional to distance.
#### Components Required
##### Hardware: ATmega328, Power supply (5v), LCD hd_44780_E, 1000uF capacitor, 10KΩ resistor (2 pieces) , HC-SR04 sensor.
##### Software: Simulide, Visual Studios.

## Research
 
##### An ultra sonic sensor is based on the measurement of the time of flight of an ultrasonic pulse, which is reflected by the ground. A constrained optimization technique is employed to obtain reflected pulses that are easily detectable by means of a threshold comparator. Manual distance measuring is always done at the expense of human error. Precise and fix measurement of low range distance, is the main objective for this project. .This project is used to measure the distance by using ultrasonic sensors.
 
## General Features

### Major activities of the manual system is automated, which increases its throughput.
##### • Vehicle detection for car wash and automotive assembly.
##### • People detection for counting.
##### • Used in terrain monitoring robots.
 
## SWOT ANALYSIS
### Strengths:
##### • Measure the distance which wil be easy to conﬁgure and handle.

### Weakness:
##### • we cannot tell you the exact distance or location of the obstacle
    
### Opportunities:
#####     • New markets or services
    
### Threats:
#####  • Adverse demograghic changes
 
## 4 W's and 1 H
#### What:
#####   Distance is a numerical measurement of how far apart objects or points are.Ultrasonic sensor provides an easy way in distance measurement.
#### Why:
#####   Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. It is used in several applications.
#### When:
#####    The ultrasonic sensor emits a high-frequency sound pulse and calculates the distance depending upon the time taken by the echo signal to travel back after reflecting from the desired target. The speed of sound is 341 meters per second in air. After the distance is calculated, it will be displayed on the LCD display.
#### Where:
#####    Measuring liquid level, checking proximity and even more popularly in automobiles to assist in self-parking or anti-collision systems.
#### How:
#####   This project, we have used the HC-SR04 Ultrasonic Sensor with ATMEGA328 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO.
  
## Details requirements
### High Level Requirements:
| ID | Description | Status |
|------| ------| ------|
| HLR1 | Enable ICP Interrupt | Implemented
|HLR2  | Enable rising edge detection,noise cancellation | Implemented
|HLR3  | Enable internal pullups on PORTC PINS  SDA(PC4) ,SCL(PC5) |	Implemented
|HLR4  |  I2C and LCD |	Implemented

#### Low Level Requirements:

| ID | Description | Status |
|-------|------|------|
| LR01 |The Timer count (OCR2A) of Timer2 was chosen | Implemented |
| LR02 |Timer2 of ATMEGA328p is used to generate a Trigger pulse of 20uS,  | Implemented |
| LR03 |The prescaler of this unit was chosen, such that the resolution of pulse-width is 16uS. | Implemented |

