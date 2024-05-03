# ECE445_Bike_Theft_Detector
Lab notebook github repo
## 2/18 - 2/24
- Design review.
- Researched bluetooth connectivity with cell phone.
- [ESP32 CAM Research](https://randomnerdtutorials.com/esp32-cam-ai-thinker-pinout/)
- Discovered many problems with 3.3 volt input of camera through online reccomendations
- ![image](https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/11ba540a-e1da-436e-9d32-f363bf612222)
- Ordered FTDI programmer for camera.
- Discussed with team how to calibrate bike lock. Determined closed loop within the bike lock was best.
## 3/2 - 3/9
- Completed teamwork evaluation.
- Researched Wi-Fi and ESP32 Programming.
- Preliminary testing of camera with Arduino IDE example code.
## 3/10 - 3/16 
- Spring Break
- [Basic ESP32 Telegram Example](https://www.youtube.com/watch?v=v36c7-s3jvA&t=270s&ab_channel=ViralScience-ThehomeofCreativity)
- When programming the camera, we must use the ground pin on the 5v side of the board, as the right side ground pin does not work.
## 3/14 - 3/23
- Checked out development board for code testing.
- Combined my wifi and alarm programs with Brandon's bluetooth program.  
- Arduino IDE ESP32 library versions for bluetooth code and telegram code are incompatible. Had to find a new telegram library i.e. Universal Telegram Bot.
- ![image](https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/6de475d4-0aa1-428e-9315-8eb3531c7928)
## 3/24 - 3/30
- Discovered camera quality defects. Adjusted camera settings with old code and Arduino camera server example. Slight improvement.
- ![Poor Quality Camera Capture](https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/2093caae-9c16-4ee8-aee6-8bf0e01d49a0)
- ![Original Image Before Quality Diminished](https://github.com/natasha-sherlock/ECE445_Bike_Theft_Detector/assets/156775876/36271505-35a5-44d9-821f-e741b687f039)
