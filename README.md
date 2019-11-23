# My Home Assistant Configuation files
---
This is my configuration files for my [Home Assistant](https://www.home-assistant.io/). It is currently running on Docker. 

## My Devices
1. Voice Assistant
    - Google Home 01
    - Google Mini 02
    - Google Mini 03
2. Security 
    - Wyze Cam 01
    - Wyze Cam 02
    - Wyze Cam 03
    - Wyze Cam 04
3. Hub 
    - Samsung Smartthings (*This is my previous hub that provided most of my automation. In the future, I'm hoping to migrate all onto Home Assistant*)
4. Lights
    - Z-Wave dimmer x2
    - ZigBee Bulbs x5
5. Outlets
    - Samsung Smart Plug x3
    - iHome Smart Plug x1
6. Sensors
    - Door Sensors x2
    - Motion Sensors x1
7. Vacuum 
    - Samsung iRobot 

## Home Assistant File Diagram

```.yaml
.homeassistant
    |_appdaemon
    |_custom_components
        |_hacs
    |_themes
        |_theme1.yaml
        |_theme2.yaml
    |_www
        |_community
        |_imgs
        
    |_configuration.yaml
    |_ui-lovelace.yaml
    |_groups.yaml
    |_secrets.yaml

```
