# ros_bridge_esp32
This code with Arduino IDE that controls a ESP32 robot car by serial commands as following
motor movement = "o 255 255" forward, "o -255 255" turn left, "o 255 -255" turn right, "o -255 -255" backward, "o 0 0" stop
encoder value = "e" read two encoder values, "r" reset two encoder values
servo motor = "s 0 45" servo0 rotate 45 degree, "s 1 125" servo1 rotate 125 degree


# ESP32 robot car with L298N, Two Motor encoders (12V 77RPM)
<img width="987" height="477" alt="image" src="https://github.com/user-attachments/assets/ac31b5d1-e061-4b08-bec1-d670e63bd69e" />
