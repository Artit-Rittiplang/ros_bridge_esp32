# 1. ros_bridge_esp32

After connecting the robot circuit as shown below (2. ESP32 Robot Car Circuit) and uploading `Twomotor_Twoservo_LED_v1.zip`, the ESP32 robot car can be controlled using serial commands as follows:

### 1) Motor movement

| Serial Monitor Output | Action | Command |
| :---: | :--- | :--- |
| <img width="312" alt="Move Forward" src="https://github.com/user-attachments/assets/572343c0-31dc-405d-abeb-3759f351653e" /> | **Move Forward** | `o 255 255` |
| <img width="301" alt="Turn Left" src="https://github.com/user-attachments/assets/132ca432-6f85-4027-94bf-96cf488784a3" /> | **Turn Left** | `o -255 255` |
| <img width="275" alt="Turn Right" src="https://github.com/user-attachments/assets/2840744d-81ef-4495-ab81-91251d834ad9" /> | **Turn Right** | `o 255 -255` |
| <img width="272" alt="Move Backward" src="https://github.com/user-attachments/assets/1ed78993-f00d-4882-b769-a2d78fbcaf6d" /> | **Move Backward** | `o -255 -255` |
| <img width="277" alt="Stop" src="https://github.com/user-attachments/assets/b5a35ad6-a028-4573-9787-5339b4f450d2" /> | **Stop** | `o 0 0` |

### 2) Encoder values

| Serial Monitor Output | Action | Command |
| :---: | :--- | :--- |
| <img width="369" alt="Read Encoder" src="https://github.com/user-attachments/assets/c166f0fe-c1ba-42e1-b444-f432dfc04c3b" /> | **Read the two encoder values** | `e` |
| *(No output image)* | **Reset the two encoder values** | `r` |

### 3) Servo motors

| Serial Monitor Output | Action |
| :---: | :--- |
| <img width="270" alt="Servo 0" src="https://github.com/user-attachments/assets/c5cd7310-9171-41a0-a1d6-a2dcb8cad886" /> | **Servo 0 rotate 45 degrees** |
| <img width="269" alt="Servo 1" src="https://github.com/user-attachments/assets/ad6eb550-ce8b-43f9-a4ee-ddad9fc5b27c" /> | **Servo 1 rotate 125 degrees** |

### 4) Digital Pinout High/Low

| Serial Monitor Output | Action | Command |
| :---: | :--- | :--- |
| <img width="275" alt="Pin 2 High" src="https://github.com/user-attachments/assets/bc93c063-3fdb-4d13-9ef8-f5864ec5080a" /> | **Set Pin 2 HIGH (LED ON)** | `l 2 1` |
| <img width="273" alt="Pin 2 Low" src="https://github.com/user-attachments/assets/2561f9fb-43e7-4f2c-aabd-7c9674d60d36" /> | **Set Pin 2 LOW (LED OFF)** | `l 2 0` |

---

> **Note:** For more information, please refer to the attached document **“ESP32 Robot Car by Serial Port and WiFi.pdf”**.
>
> *Disclaimer: Some code examples in the PDF document are different from the uploaded code. The document is intended for basic student learning, so it is simplified and does not include all advanced features present in the firmware.*
# 2. ESP32 robot car circuit
Two motor encoders 12V 77RPM, Two servo motor sg90
<img width="987" height="477" alt="image" src="https://github.com/user-attachments/assets/ac31b5d1-e061-4b08-bec1-d670e63bd69e" />
