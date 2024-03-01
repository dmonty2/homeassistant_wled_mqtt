# homeassistant_wled_mqtt
This is a configuration.yaml example for switching wled integragion to a mqtt client.

This is an attempt to resolve an issue where the WLED light strip randomly flashes.
One suggestion was to disable Homeassistant's wled integration polls too often and causing flashes.
MQTT may reduce WLED flashing.

https://github.com/Aircoookie/WLED/issues/2480

https://github.com/home-assistant/core/issues/90676

I found disabling "automatic brightness limiter" under "LED Preferences" helped reduce flashing.

Tried disabling all Sync Interfaces except MQTT this did not fix flashing.
