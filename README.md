# ECE445_Bike_Theft_Detector
# Natasha Sherlock Lab Notebook
## 2/18 - 2/24
- Design review.
- Researched bluetooth connectivity with cell phone.
- [ESP32 CAM Research](https://randomnerdtutorials.com/esp32-cam-ai-thinker-pinout/)
- Discovered many problems with 3.3 volt input of camera through online reccomendations.
![image](https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/11ba540a-e1da-436e-9d32-f363bf612222)
- Ordered FTDI programmer for camera.
- Discussed with team how to calibrate bike lock. Determined closed loop within the bike lock was best.
## 3/2 - 3/9
- Completed teamwork evaluation.
- Researched Wi-Fi and ESP32 Programming.
- Programmed alarm with GPIO pin trigger.
- Preliminary testing of camera with Arduino IDE example code.
## 3/10 - 3/16 
- Spring Break.
- Tested Camera with Wifi hotspot. Had to set phone hotspot to maximum compatibility for it to be discoverable by the ESP32 CAM.
- [Basic ESP32 Telegram Example](https://www.youtube.com/watch?v=v36c7-s3jvA&t=270s&ab_channel=ViralScience-ThehomeofCreativity)
- When programming the camera, we must use the ground pin on the 5v side of the board, as the right side ground pin does not work. Ran into many programming issues because of this.
## 3/14 - 3/23
- Checked out development board for code testing.
- Combined my wifi and alarm programs with Brandon's bluetooth program.  
- Arduino IDE ESP32 library versions for bluetooth code and telegram code are incompatible. Had to find a new telegram library i.e. Universal Telegram Bot.
- Soldered parts of first PCB order. Missing capacitors. 
![image](https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/6de475d4-0aa1-428e-9315-8eb3531c7928)
## 3/24 - 3/30 
- Discovered that Bluetooth and Wifi share the same antenna and are therefore incompatible together
- Discovered camera quality defects. Adjusted camera settings with old code and Arduino camera server example. Slight improvement.
-  ### Poor Quality Camera Capture vs Original Camera Captures Before Quality Diminished
![image](https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/2093caae-9c16-4ee8-aee6-8bf0e01d49a0 =100x20)
 <img src= https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/36271505-35a5-44d9-821f-e741b687f039 alt="drawing" width="200"/>
## 3/31 - 4/6
- Soldered PCB.
- Encountered issues programming PCB, so we broke open a USB cable and programmed it using the D+ and D- pins.
-  Issued with PCB ESP32 constantly disconnecting from computer when attempting to program.
- Ordered PCB Cases.
## 4/7 - 4/13
- Added feature to remotely reset camera for demonstration purposes.
- Bug in program that triggers alarm to sound upon camera reset. Corrected by resetting alarm variable.
- Drilled PCB cases for bike cable wire.
- Hot glued bike lock to PCB case.
## 4/14 - 4/20
- Mock Demo.
- Added light indicator feature for battery life. Drilled additional holes for button.
- Waterproofed PCB case with hot glue and tape.
- Ran battery life tests.
- Ran decible tests.
- Functionality Broke.
## 4/21 - 4/27
- Applied velcro to Camera Module case.
- Extra credit video.
- Final Demo
