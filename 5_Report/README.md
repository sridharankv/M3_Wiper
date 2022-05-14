# Report

# ABSTRACT

Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen.The previous system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled.Thus, this system is proposed to solve these problems. The objectives of this project are to upgrade the older cars system by providing automatic wiping system, to improve the system by using sensor with actuator and to design a basic program that will fully operate with the system. The concept of this proposed wiper system is similar with other existing conventional wiper.It is recommended that the system to have a study on the wiper material that been used to make a wiper because the driver at hot and climate country are facing the problems regards to the wiper material.
## INTRODUCTION

Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on each headlight. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. The wiper itself has about six parts called pressure points or claws that are small arms under the wiper.The concept of this wiper system is similar with other conventional wiper, yet this system will be upgraded to an automatic control system by using a controller.Whenever the water hit a dedicated sensor that located on windscreen, it will send a signal to move on the wiper motor.Once water is not detected by sensor, the wiper will automatically stop. This will help the driver to give more concentration and reduce the car accident. probability. 

## Research 

### Objective 

The goal of this project is to a develop a “WiperControlSystem”. This is very useful  wiper are designed and made to clear the water from a windscreen.


## Requirnments for this project are

### Software Requirnments

STM32 CUBE IDE

### Hardware Requirnments

STM32F4O7VG MICROCONTROLLER BOARD

## Description

### STM32F407VG

The STM32F407 Kit makes it simple for users to construct audio-based applications by utilising the high-performance STM32F407 microcontrollers' capabilities. It includes an ST-LINK embedded debug tool, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector. The STM32F4 DISCOVERY kit now includes Ethernet connectivity, an LCD display, and other features. The Arm® Cortex®-M4 32-bit RISC processor, which works at up to 168 MHz, is at the heart of the STM32F405xx and STM32F407xx families.

### Features of STM32F407VG

* The STM32F407VGT6 microcontroller contains a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM in a LQFP100 package.
* STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 on-board ST-LINK/V2 or ST-LINK/V2-A (new order code)
* USB ST-LINK with three different interfaces and the option to re-enumerate.
* Debug port for virtual com port (with new order code only)
* Large-scale archiving (with new order code only)
* Board power is supplied through USB or an external 5 V supply source. * External application power supply is available in 3 V and 5 V.

### Benefits 
* This microcontroller is used in printers and scanners, as well as heating, ventilation, and air conditioning and security systems.
* This module can be found in a wide range of everyday items.

### Defining Our System

Assume the microcontroller is the automobile. When the button is pressed, the first led (red) turns on, the wiper starts, and the second led (blue) turns on at the appropriate rate. The third led (green) will turn on if the button is pressed again, and the wiper speed will be increased in contrast to the previous one. The fourth press will activate the fourth led (orange) and raise the wiper speed in accordance with the previous one. After the fifth click, the microcontroller (vehicle) is turned off.

## High Level Requirements
| ID | Description | Category |	Status |
|:-: |:-----------:|:--------:|:------:|
| HR01 | Can be able to keep the windscreen clean | Technical | Implemented |
| HR02 | Can be able to windshield wipers clear the windshield of rain and snow | Technical | Implemented |
| HR03 | Can be able to improve headlight visibility at night | Technical | Implemented |
| HR04 | Can be able to driver to have a clear view | Technical | Implemented |


## Low Level Requirements
| ID | Description | HLR ID | Status (Implemented/Future) |
|:-:|:-----------:|:------:|:---------------------------:|
| LR01 | Driver can be able see the windscreen clean | HR01 | IMPLEMENTED |
| LR02 | Same operation for windshield wipers clear the windshield of rain and snow | HR02 | IMPLEMENTED |
| LR03 | Same operation for improve headlight visibility at night | HR03 | IMPLEMENTED |
| LR04 | Same operation for driver to have a clear view | HR04 | IMPLEMENTED |

# 0utput

## WHEN WIPER IN ON STATE

![alt text](https://github.com/sridharankv/M3_WiperControlSystem/blob/main/6_Output/output/ON%20STATE.png)

## WHEN WIPER SPEED IS LOW

![alt text](https://github.com/sridharankv/M3_WiperControlSystem/blob/main/6_Output/output/LOW%20WIPER%20SPEED.png)

## WHEN WIPER SPEED IS MODERATE

![alt text](https://github.com/sridharankv/M3_WiperControlSystem/blob/main/6_Output/output/WIPER%20SPEED%20IS%20MODERATE.png)

## WHEN WIPER SPEED IS HIGH

![alt text](https://github.com/sridharankv/M3_WiperControlSystem/blob/main/6_Output/output/HIGH%20WIPER%20SPEED.png)

## WHEN WIPER IN OFF STATE

![alt text](https://github.com/sridharankv/M3_WiperControlSystem/blob/main/6_Output/output/OFF%20STATE.png)

