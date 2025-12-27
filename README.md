# 1. ros_bridge_esp32

After connecting the robot circuit as shown below (2. ESP32 Robot Car Circuit) and uploading Twomotor_Twoservo_LED_v1.zip, the ESP32 robot car can be controlled using serial commands as follows:
  1) Motor movement

    "o 255 255" : move forward

    "o -255 255" : turn left
    
    "o 255 -255" : turn right
    
    "o -255 -255" : move backward
    
    "o 0 0" : stop
    
  3) Encoder values
     
    "e" : read the two encoder values
    
    "r" : reset the two encoder values
    
  5) Servo motors
     
    "s 0 45" : servo0 rotate 45 degrees
    
    "s 1 125" : servo1 rotate 125 degrees

For more information, please refer to the attached document “ESP32 Robot Car by Serial Port and WiFi.pdf”.
Some code examples in the document are different from the uploaded code because the document is intended for basic student learning, so it is simplified and does not include advanced features.

# 2. ESP32 robot car circuit
Two motor encoders 12V 77RPM, Two servo motor sg90
<img width="987" height="477" alt="image" src="https://github.com/user-attachments/assets/ac31b5d1-e061-4b08-bec1-d670e63bd69e" />
