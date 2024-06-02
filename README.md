# esphome-rack-temp
esphome config for monitoring 100K ohm NTC 3950 Thermistors


```
docker run --rm -v "${PWD}":/config -it ghcr.io/esphome/esphome wizard livingroom.yaml
```

```
docker run --rm --privileged -v .\:/config --device=/dev/ttyUSB0 -it ghcr.io/esphome/esphome run modbus-acculevel.yaml
```

