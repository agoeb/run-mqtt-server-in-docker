# Running an MQTT with support for Websocket

> In order to build, test and run an interactive webapp, that use MQTT<br />
> As a Software Engineer<br />
> I want to quickly get a running MQTT-broker with websockets support

This repo provides the minimal config needed to quickly run an MQTT-broker assuming you have docker available on your local machine.

## Running an MQTT-server

1. Clone this repo: `git@github.com:mcbeelen/run-mqtt-server-in-docker.git`
2. Run `docker-compose up`

## Local errors

This will likely result in a `docker: Error response from daemon` with the details:
```
The path ${YOUR_PROJECT_LOCATION}/mqqt/config/mosquitto.conf is not shared from the host and is not known to Docker.
You can configure shared paths from Docker -> Preferences... -> Resources -> File Sharing.
```

Just follow the provided suggestion and try again.
