# Home Assistant Configuration

Configuration files for my [HomeAssistant](https://home-assistant.io) instance

## Credits

The "slate" dark theme has been created by [SneakyPie/Sean](https://github.com/seangreen2) 

## Current Configuration

* Raspberry Pi 3 Model B using the [venv](https://www.home-assistant.io/docs/installation/virtualenv/) installation method
* Let's encrypt 
* MQTT 
* NodeRed (in docker) 

### Devices

* Philips Hue Bridge
* PHilips Hue White & Color Ambiance
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
* Raspberry system monitor
* Kodi Screensaver sensor (via template) 
* Dark Sky + Meteo France weather sensor

### Automation
Most of the automation is handled through NodeRed

* Manage startup configuration when Homeassistant starts

### Switches
* Command line switches to automate Sonarr/Radarr/Mopidy when NAS is on.
* Flux 
* WOL for PC

### Preview

[Home Assistant Gif](https://github.com/jcoin/homeassistant-config/HA.gif "Home Assistant Preview")

### To-Do

* Integrate with Travis-CI
* Automation cleanup

