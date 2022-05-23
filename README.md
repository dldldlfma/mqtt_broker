# Mosquitto MQTT Broker using docker-compose

## Prerequisites

- mosquitto(https://mosquitto.org/download/)
- docker(https://docs.docker.com/engine/install/)
- docker-compose(if you use windows or mac, after docker install, you can use docker-compose)

## Rnn

```bash
./run.sh
```

or

```bash
docker-compose up
```

## Test

```
mosquitto_pub -h localhost -p 1883 -t test 'message'
```
