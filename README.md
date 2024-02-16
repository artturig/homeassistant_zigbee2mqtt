# homeassistant_zigbee2mqtt
config files to run Home Assistant Mqtt broker and zigbee2mqtt on rasberry pi

## remove starting h_ m_ z_ from files and place to folders following

Zigbee2MQTT/docker-compose.yaml
Zigbee2MQTT/data/configuration.yaml

homeassistant/homeAssistant/docker-compose.yaml
homeassistant/homeAssistant/data/configuration.yaml

mqtt/mqtt5/docker-compose.yaml
mqtt/mqtt5/config/configuration.yaml

## got to all folders and start docker with command
docker compose up -d

## sites used

https://www.zigbee2mqtt.io/guide/installation/01_linux.html#determine-location-of-the-adapter-and-checking-user-permissions to find USB settings needed for zigbee2mqtt  
https://www.zigbee2mqtt.io/guide/getting-started/  
https://github.com/sukesh-ak/setup-mosquitto-with-docker  
https://www.home-assistant.io/installation/linux  

