# esphome-illuminatio
Dimmable LED drivers controller based on ESP Home with HomeAssistant integration via MQTT

in order to compile and deploy this project you need to get https://esphome.io


```podman run --rm -v "${PWD}":/config --device=/dev/ttyUSB0 -it esphome/esphome ./illuminatio.yml run```