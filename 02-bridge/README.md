# MQTT to InfluxDB Bridge for Tasmota Devices 

## Build

```sh
$ docker build -t revil-O/mqttbridge .
```


## Run

```sh
$ docker run -d --name mqttbridge revil-O/mqttbridge
```


## Dev

```sh
$ docker run -it --rm -v `pwd`:/app --name python python:3.7-alpine sh
```
