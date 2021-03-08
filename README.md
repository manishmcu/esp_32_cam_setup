# esp_32_cam_setup

Update the "Preferences" with following
https://dl.espressif.com/dl/package_esp32_index.json

Tutorial UTube: https://youtu.be/-GDlk6qgQ_E
Boadr: ESP Wrover Module

C:\Program Files (x86)\Arduino\libraries\WiFi\src
--> going here rename the "WiFi.h" file as "ArduinoWiFi.h"

#define CAMERA_MODEL_AI_THINKER //For on-board camera
//#define CAMERA_MODEL_WROVER_KIT //For other camera module

after upload-> reset--->unplug shorted wire---> reset---> find ip for VID stream

MY IP= http://192.168.43.87/

open browswe and start vedio stream stream

Wire connection is following

<img src="Wire Connection/connection DIA.png" height=350> <img src="Wire Connection/connection.jpeg" height=350>
