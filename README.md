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
### Hardware
```
The HAT
A 3.7 Lithium ion rechargeble battery
A USB B to USB B micro cable
A laptop (Windows/MacOS/Linux)
5V power supply
STM32 Microcontroller
```
### Software
```
Atollic Studios
```

## Setting up software

Download the Atollic Studios from [this](https://www.st.com/en/development-tools/truestudio.html#:~:text=Featured%20Videos-,Description,easy%20and%20efficient%20development%20process.)



## Connecting the HAT

### Step 1: Powering up
```
Connect the HAT to the STM32, Make sure the usb port of the micro and the microcontroller are lined up 
- if the pins are mismatched, this can lead to a short circuit
The Green LED should be on when Plug is detected
```
### Step 2: Connecting to your laptop
```
Connect the USB cable to your laptop
Then connect the micro USB B to the HAT while holding the reset button(Blue button) of the micro controller.
```
### Step 3: Programming the HAT

Open Up your Atollic Studios, fork code from this [respiratory](https://github.com/ltnlutendo/EEE3088F-Team-8)
Paste this on the terminal and Run it to the micro controller.
Set the maximum variable to Max = 3 (This will set the maximum number of people allowed to enter to 3).
The blue LED will flash twice once the code is succesfully copied to the HAT's memory.

### Step 4: Getting ready to test

```
Put the hat flat on the table such that the sensors are not obstructed (1m unobstructed minimum distance).
```
### Step 5: Test

```
Wave your hand on top of the HAT 3 times, The buzzer should beep indicating maximum number of people entered.
```
### Well Done! You're all set up.

### Project Credits
- Power Submodule  - [Lutendo Mulaisi](https://github.com/ltnlutendo) 
- Sensor Submodule   - [Munashe Chihota](https://github.com/MunasheC)
- Interfacing Submodule - [Lisakhanya Miyani](https://github.com/LisakhanyaMiyana)
## How to contribute
You can contribute to this project using these [guidelines](https://www.contributor-covenant.org/)

## License
MIT License

Copyright (c) 2022 Team 8

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
