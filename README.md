# EEE3088F-Team-8
Team collaboration for the EEE3088F 2022, HAT project



The HAT will serve primarily as a covid compliancy monitor for enclosed public venues like
lecture theatres, classrooms and supermarkets. The Hat will be connected to a STM32
discovery board which will handle computations and other processing. It will make use of
ultrasonic sensors that will be mounted on the venue entrance to capture the number of people
entering the venue. It will also incorporate pressure and temperature sensors to specifically
monitor room ventilation and determine whether the room is safe enough for its occupants.
Besides, covid related uses, the HAT could be used to compile statistical records on lecture
attendance or supermarket peak times. Furthermore, it can be used to monitor overcrowding on
shuttles like the Jammie buses in accordance with traffic and road safety regulations.

This is an ongoing project which is constantly improved 

## What you will need:
```
*Hardware*
The HAT
A 3.7 Lithium ion rechargeble battery
A USB B to USB B micro cable
A laptop (Windows/MacOS/Linux)
5V power supply
STM32 Microcontroller

*Software*
Atollic Studios
```

## Setting up software
```
Download the Atollic Studios from this [link](https://www.st.com/en/development-tools/truestudio.html#:~:text=Featured%20Videos-,Description,easy%20and%20efficient%20development%20process.)
```


## Connecting the HAT

### Step 1
```
Connect the HAT to the STM32, Make sure the usb port of the micro and the microcontroller are lined up - if the pins are mismatched, this can lead to a short circuit
The Green LED should be on when Plug is detected
```
### Step 2
```
Connect the USB cable to your laptop
Then connect the micro USB B to the HAT while holding the reset button(Blue button) of the micro controller
```
### Step 3
```
Open Up your Atollic Studios, fork code from this [respiratory](https://github.com/ltnlutendo/EEE3088F-Team-8)
Paste this on the terminal and Run it to the micro controller
The blue LED will flash twice once the code is succesfully copied to the HAT's memory
```
### Step 4

```
Put the hat flat on the table such that the sensors are not obstructed (1m unobstructed minimum distance)
```
## First use - Hello World

## How to contribute
