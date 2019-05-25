# SolidCake420 Home Assistant Configuration

Welcome to my Home Assistant!

Please understand, that the config is very much a work-in-progress - I'm still quite new to Home Assistant and have a lot of pending hardware and UI changes planned (please check TO-DO.MD for future plans).
I live in the U.K., keep that in mind as some of the integrations/devices might not be available in other countries. 

#### Navigation:

* lovelace-ui.yaml should be copied to Lovelace UI Raw Config Editor
* screenshots/gifs are in examples folder and don't get updated with every commit

![shield1](https://img.shields.io/badge/Home%20Assistant-0.93.1-green.svg "HA version")
![shield2](https://img.shields.io/github/commit-activity/m/solidcake420/home_assistant.svg "commit-activity")
![shield3](https://img.shields.io/github/last-commit/solidcake420/home_assistant.svg "last-commit")
![shield4](https://img.shields.io/github/stars/solidcake420/home_assistant.svg "stars")

If you want to buy me a coffee, that would be much appreciated. :)

<a href="https://www.buymeacoffee.com/B8KgOCPIb" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

# Desktop Lovelace
![desktop](/example/example_lovelace_pc.gif "Lovelace example on desktop")

## [Screenshots](https://imgur.com/a/ALbkssC)


## Used Hardware

- [Raspberry Pi 3 Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/), running Hass.IO 2.11, Home Assistant 0.93.1
 
Network:

- [BT Smart Hub Gen 1](https://shop.bt.com/products/bt-smart-hub-088138-C6NX.html)
- [TP-Link TL-WR702N](https://www.tp-link.com/uk/home-networking/wifi-router/tl-wr702n/)
- [TP-Link TL-PA7020P](https://www.tp-link.com/uk/home-networking/powerline/tl-pa7020p-kit/)

Google: 

- [Chromecast 2nd gen](https://store.google.com/ph/product/chromecast_2015)
- [Chromecast Audio](https://www.google.com/chromecast/audio/explore/)
- [Google Home](https://store.google.com/product/google_home)
- 4x [Google Home Mini](https://store.google.com/product/google_home_mini)


Hue: [ZigBee]

- [2nd Gen Hue Bridge](https://www2.meethue.com/en-gb/p/hue-bridge/8718696516850)
- [Hue Motion Sensor](https://www2.meethue.com/en-gb/p/hue-motion-sensor/8718696743171)
- [Hue Dimmer Switch](https://www2.meethue.com/en-gb/p/hue-dimmer-switch/8718696743157)
- 3x [E27 Colour Gen 3 Hue Bulbs](https://www2.meethue.com/en-gb/p/hue-white-and-colour-ambience-single-bulb-e27/8718696592984)
- 1x [Hue Gen 2 Lighhtstrip Plus](https://www2.meethue.com/en-gb/p/hue-white-and-colour-ambience-lightstrip-plus-eu-uk-base/7190155PH)
- 2x [E27 Hue White Bulbs](https://www2.meethue.com/en-gb/p/hue-white-dual-pack-e27/8718696729113)
- 2x [INNR E27 RB 285 C 3rd party Bulbs](https://shop.innrlighting.com/en/shop/143/smart-bulb-colour-e27-z3.0)
- 2x [GLEDOPTO RGB+CCT 3rd party LED Controllers](https://www.aliexpress.com/store/product/gledopto-1ID-2ID-rgb-cct-led-controller-ZIGBEE-ZLL-DC12-24V-strip-light-controller-rgbw-cw/3685003_32969239825.html)

ZigBee2MQTT [ZigBee]

- [CC2531 ZigBee USB Stick](https://www.amazon.co.uk/s?k=cc2531)
- [Xiaomi Aqara Single Light Wall Switch](https://xiaomi-mi.com/sockets-and-sensors/aqara-smart-light-wall-switch-zigbee-version-single-key/)
- [Xiaomi Aqara Window Door Sensor](https://xiaomi-mi.com/sockets-and-sensors/xiaomi-aqara-window-door-sensor/)
- [Xiaomi Aqara Temperature and Humidity Sensor](https://xiaomi-mi.com/sockets-and-sensors/aqara-temperature-and-humidity-sensor/)
- [Ksentry Electronics ZigBee Switch](https://ksentry.manufacturer.globalsources.com/si/6008837134660/pdtl/ZigBee-module/1162731630/zigbee-on-off-controller-modules.htm)

ESP8266: [WiFi, all running ESPHome firmware]

- 3x [Sonoff S20](https://sonoff.itead.cc/en/products/residential/s20-socket)
- 1x [Sonoff Basic](https://sonoff.itead.cc/en/products/sonoff/sonoff-basic)
- 1x [Sonoff TH16](https://sonoff.itead.cc/en/products/sonoff/sonoff-th) + [AM2301 sensor](https://sonoff.itead.cc/en/products/accessories/am2301)
- 1x [Generic GMYLE Tuya plug](https://www.amazon.co.uk/gp/product/B074SXKQRZ)
- 1x [LINGANZH SWB1 Smart Power Strip](https://amazon.co.uk/gp/product/B07FT8TH3W)

OTHER:
- [Dyson DP01 Pure Cool Link Desk Fan](https://www.dyson.com/purifiers/dyson-dp01-pure-cool-link-desk-white-silver.html)
- [SONY PlayStation 4](https://www.sony.co.uk/electronics/playstation-systems/playstation-4)
- [Broadlink RM Mini 3](http://www.ibroadlink.com/rmMini3/)


## Components/custom cards used


Add-Ons:

- [Configurator](https://www.home-assistant.io/addons/configurator/)
- [ESPHome](https://github.com/esphome/hassio)
- [Mosquitto MQTT broker](https://www.home-assistant.io/addons/mosquitto/)
- [SSH server](https://www.home-assistant.io/addons/ssh/)
- [Check HA configuration](https://www.home-assistant.io/addons/check_config/)
- [Samba share](https://www.home-assistant.io/addons/samba/)
- [zigbee2mqtt](https://github.com/danielwelch/hassio-zigbee2mqtt)


Integrated through [Home Assistant Cloud](https://www.home-assistant.io/cloud/):

- Remote Access
- Google Assistant 


Official integrations:

- [MQTT](https://www.home-assistant.io/components/mqtt/)
- [Google Cast](https://www.home-assistant.io/components/cast/)
- [Phillips Hue](https://www.home-assistant.io/components/hue/)
- [PlayStation 4](https://www.home-assistant.io/components/ps4/)
- [ESPHome](https://www.home-assistant.io/components/esphome/)


Official components:

- [HTML5 Notifications](https://www.home-assistant.io/components/html5/)
- [DarkSky Weather](https://www.home-assistant.io/components/weather.darksky/)
- [Dyson Air Purifier](https://www.home-assistant.io/components/dyson/)
- [BT Smart Hub Device tracker](https://www.home-assistant.io/components/bt_smarthub/)
- [System Monitor](https://www.home-assistant.io/components/openhardwaremonitor/)
- [World Air Quality Index](https://www.home-assistant.io/components/waqi/)
- [Workday Binary Sensor](https://www.home-assistant.io/components/workday/)
- [Spotify](https://www.home-assistant.io/components/spotify/)
- [Broadlink](https://www.home-assistant.io/components/broadlink/)
- [Speedtest.net](https://www.home-assistant.io/components/speedtestdotnet/)


Unofficial/custom components:

- [Custom Updater](https://github.com/custom-components/custom_updater)
- [Breaking Changes](https://github.com/custom-components/breaking_changes)


Custom Lovelace components:

- [Weather Card](https://github.com/bramkragten/custom-ui/tree/master/weather-card)
- [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
- [Mini Media Player](https://github.com/kalkih/mini-media-player)
- [Light Entity Row](https://github.com/custom-cards/light-entity-row)
- [Slider Entity Row](https://github.com/thomasloven/lovelace-slider-entity-row)
- [Card Tools](https://github.com/thomasloven/lovelace-card-tools)
- [Card Modder](https://github.com/thomasloven/lovelace-card-modder)
- [Button Card](https://github.com/custom-cards/button-card) (currently not in use)
- [Fold Entity Row](https://github.com/thomasloven/lovelace-fold-entity-row)
- [Compact custom header](https://github.com/maykar/compact-custom-header)
- [Swipe Card](https://github.com/bramkragten/custom-ui/tree/master/swipe-card)
- [Lovelace Swipe Navigation](https://github.com/maykar/lovelace-swipe-navigation)
- [Vertical Stack In Card](https://github.com/custom-cards/vertical-stack-in-card)

Other:

- [HassIQ](https://github.com/alanfischer/hassiq)
- [Hass-bha-icons](https://github.com/hulkhaugen/hass-bha-icons)
