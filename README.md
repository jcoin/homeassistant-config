# Home Assistant Configuration [![CircleCI](https://circleci.com/gh/jcoin/homeassistant-config/tree/master.svg?style=svg)](https://circleci.com/gh/jcoin/homeassistant-config/tree/master)

Configuration files for my [HomeAssistant](https://home-assistant.io) instance

## Current Configuration

* Raspberry Pi 3 Model B using the [venv](https://www.home-assistant.io/docs/installation/virtualenv/) installation method
* Let's encrypt 
* MQTT 
* NodeRed (in docker) 
* Pi-Hole (in docker)
* Sonarr (in docker)
* Radarr (in docker)
* Mopidy

### Devices

* Philips Hue Bridge
* Philips Hue White & Color Ambiance
* Philips Hue Dimmer Switch
* Philips Hue Filament Bulb
* TRADFRI IKEA lights
* Google Home & Google Home mini
* OSRAM Smart+ Plug
* Rasperry Pi 3 running [OSMC](https://osmc.tv/) with Kodi 18
* Nexus 10 running Kodi 18.2
* Android Phones with Tasker
* Bruh Multisensor & others Esp8266 devices with [ESPHome](https://esphome.io/) 
* Sonoff T1 with [ESPHome](https://esphome.io/)

### Sensors

* [Let's Encrypt Certificate Expiration Sensor](https://www.home-assistant.io/components/sensor.cert_expiry/)
* [File Size Sensor for home assistant db](https://www.home-assistant.io/components/filesize/) 
* [Linky Sensor](https://www.home-assistant.io/components/linky/) 
* Various [MQTT](https://www.home-assistant.io/components/sensor.mqtt/) sensors
* [Pi-hole](https://www.home-assistant.io/components/pi_hole/) sensor
* [Last.fm](https://www.home-assistant.io/components/lastfm/) sensor
* [Sonarr](https://www.home-assistant.io/integrations/sonarr/) sensor
* Raspberry system monitor
* Kodi Screensaver sensor (via template) 
* Dark Sky + Meteo France weather sensor

### HACS

* Config Template Card
* Hue sensor custom component
* Upcoming Media Card
* Layout Card
* Entity Attribute Card
* Midnight Theme
* Card Tools
* Slider Entity Row
* Trakt
* Gap Card

### Automation
Most of the automation is handled through appdaemon & NodeRed

* Manage startup configuration when Homeassistant starts

### Switches
* Command line switches to automate Sonarr/Radarr/Mopidy when NAS is on.
* Flux 
* WOL for PC

### Preview

![Home Assistant Gif](https://github.com/jcoin/homeassistant-config/blob/master/HA.gif)

### To-Do

* FIP integration via Radio France Open API.
