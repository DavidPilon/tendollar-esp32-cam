# tendollar-esp32-cam
esp32-cam based on tendollarwebcam, using arduino ide

code based on https://github.com/geeksville/TenDollarWebcam

edit OV2640.cpp for resolution ( found UXGA just takes to much out of the esp32, with sxga it works at a few fps)

Changes: 

    factory reset button was incorrect, so device always came up n factory reset mode
    easily changed from autoip to manual by:
       uncomment ssid/password, wifibegin, 
       comment out WiFi.mode(WIFI_STA), and anotheything to do with autowifi (autowifi, a. etc)
    included all the aditional libaries needed so no longer need platforio, and can just use Arduino IDE)

Follow https://github.com/geeksville/AutoWifi to conenct to wifi initially
