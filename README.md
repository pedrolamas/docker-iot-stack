# NanoPi NEO2 Docker Configuration

This is personal docker configuration currently up and running inside a [NanoPi NEO2](https://www.friendlyarm.com/index.php?route=product/product&product_id=180) small board computer (SBC).

My NanoPI is currently running [Armbian Bionic](https://www.armbian.com/nanopi-neo-2/).

To install docker, please use the [convenience script](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-using-the-convenience-script).

To run, just enter the root folder and run:

```sh
docker-compose up -d
```

Feel free to send questions or PR's with improvements!

## Images

### AdGuard Home

Free and open source, powerful network-wide ads & trackers blocking DNS server.

* Image: [adguard/adguardhome](https://hub.docker.com/r/adguard/adguardhome)

### Nginx

Nginx (pronounced "engine-x") is an open source reverse proxy server for HTTP, HTTPS, SMTP, POP3, and IMAP protocols, as well as a load balancer, HTTP cache, and a web server (origin server).

* Image: [nginx](https://hub.docker.com/_/nginx)

### Home Assistant

Home Assistant is an open source home automation tool that puts local control and privacy first.

* Image: [homeassistant/home-assistant](https://hub.docker.com/r/homeassistant/home-assistant)

### Node-RED

Node-RED is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

* Image: [nodered/node-red](https://hub.docker.com/r/nodered/node-red)

### Eclipse Mosquitto

Eclipse Mosquitto is an open source implementation of a server for version 3.1 and 3.1.1 of the MQTT protocol.

* Image: [eclipse-mosquitto](https://hub.docker.com/_/eclipse-mosquitto)

### Zigbee2Mqtt

Zigbee2Mqtt allows you to use your Zigbee devices without the vendors bridge or gateway.

* Image: [koenkk/zigbee2mqtt](https://hub.docker.com/r/koenkk/zigbee2mqtt)

### Telegraf

Telegraf is an agent for collecting metrics and writing them to InfluxDB or other outputs.

* Image: [telegraf](https://hub.docker.com/_/telegraf)

### mariadb

MariaDB is a community-developed fork of MySQL intended to remain free under the GNU GPL.

* Image: [mariadb](https://hub.docker.com/_/mariadb)

### Grafana

Grafana is the open source analytics and monitoring solution for every database.

* Image: [grafana/grafana](grafana/grafana:7.0.0-beta1)
  Tag: 7.0.0-beta1

### Portainer

Build and manage your Docker environments with ease today.

* Image: [portainer/portainer](https://hub.docker.com/r/portainer/portainer)
