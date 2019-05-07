# SolidCake420 Home Assistant Configuration

Hi, I've been playing with Home Assistant for about a month now, please feel free to use any of my stuff.

The setup is still a bit messy, as I have a lot of things WIP or pending for hardware.

PS: lovelace-ui.yaml should be copied to Lovelace UI Raw Config Editor


If you want to buy me a coffee, that would be much appreciated. :)

<a href="https://www.buymeacoffee.com/B8KgOCPIb" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>

# Desktop Lovelace
![desktop](/example/example_lovelace_pc.gif "Lovelace example on desktop")

# Mobile Lovelace
![mobile1](/example/example_lovelace_mobile1.gif "Lovelace example on mobile 1")
![mobile2](/example/example_lovelace_mobile2.gif "Lovelace example on mobile 2")

[Screenshots](https://imgur.com/a/ALbkssC)


## Used Hardware

- [Raspberry Pi 3 Model B](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/), running Hass.IO 2.11, Home Assistant 0.92.2
 
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


ESP8266: [WiFi, all running ESPHome firmware]

- 3x [Sonoff S20](https://sonoff.itead.cc/en/products/residential/s20-socket)
- 2x [Sonoff Basic](https://sonoff.itead.cc/en/products/sonoff/sonoff-basic)
- 1x [Sonoff TH16](https://sonoff.itead.cc/en/products/sonoff/sonoff-th) + [AM2301 sensor](https://sonoff.itead.cc/en/products/accessories/am2301)
- 1x [Generic GMYLE Tuya plug](https://www.amazon.co.uk/gp/product/B074SXKQRZ/ref=ppx_yo_dt_b_search_asin_title)

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


Integrated through [Home Assistant Cloud](https://www.home-assistant.io/cloud/):

- Remote Access
- Google Assistant 


Official integrations:

- [MQTT](https://www.home-assistant.io/components/mqtt/) (currently not in use)
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
- [Fast.com](https://www.home-assistant.io/components/fastdotcom/)
- [World Air Quality Index](https://www.home-assistant.io/components/waqi/)
- [Workday Binary Sensor](https://www.home-assistant.io/components/workday/)
- [Spotify](https://www.home-assistant.io/components/spotify/)
- [17track.net](https://www.home-assistant.io/components/seventeentrack/)
- [Broadlink](https://www.home-assistant.io/components/broadlink/)


Unofficial/custom components:

- [Custom Updater](https://github.com/custom-components/custom_updater)


Custom Lovelace Cards:

- [Weather Card](https://github.com/bramkragten/custom-ui/tree/master/weather-card)
- [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
- [Mini Media Player](https://github.com/kalkih/mini-media-player)
- [Light Entity Row](https://github.com/custom-cards/light-entity-row)
- [Slider Entity Row](https://github.com/thomasloven/lovelace-slider-entity-row)
- [Card Tools](https://github.com/thomasloven/lovelace-card-tools)
- [Card Modder](https://github.com/thomasloven/lovelace-card-modder)
- [Button Card](https://github.com/custom-cards/button-card)


Other:

- [HassIQ](https://github.com/alanfischer/hassiq)
- [Hass-bha-icons](https://github.com/hulkhaugen/hass-bha-icons)