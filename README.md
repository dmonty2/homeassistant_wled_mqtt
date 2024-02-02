# homeassistant_wled_mqtt
This is a configuration.yaml example for switching wled integragion to a mqtt client.

Homeassistant's wled integration polls the controller too often causing it to flash white.
Disabling Homeassistant's wled integration the flickering stops.  MQTT causes WLED
to flash less less.

https://github.com/Aircoookie/WLED/issues/2480

https://github.com/home-assistant/core/issues/90676

One suggestion in the bug reports is to switch to MQTT which is not as polished.
This might not resolve flashing white issue.
