# shiot
Smart Home IoT Personal Documentation

## Matter

### Build CHIP Project

- Consider this [link](https://project-chip.github.io/connectedhomeip-doc/guides/BUILDING.html) to build the entire chip project for testing


## IoT Core

### Home Assistant Project

- We can use docekr version of the home assistant project using the following command:
```bash
 docker run -d \             
  --name homeassistant \
  --privileged \
  -e TZ=Asia/Tehran \
  -v /home/mohy/work/podbox/config:/config \
  -v /run/dbus:/run/dbus:ro \
  --network=host \   
``` 
- We can add integrations by adding the integration src to `/config/custom_components/` manually. 

## Devices

### Tuya

### Xiaomi

 - Yeelink
 - Mi BLE temperature sensor

