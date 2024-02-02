# homeassistant_wled_mqtt
This is a configuration.yaml example for switching wled integragion to a mqtt client.

Homeassistant's wled integration polls the controller too often causing it to flicker.
https://github.com/Aircoookie/WLED/issues/2480
https://github.com/home-assistant/core/issues/90676
One suggestion in the bug reports is to switch to MQTT which is not as pollished but at least it doesn't flicker.
