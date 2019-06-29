# NanoPi NEO2 Docker Configuration

This is personal docker configuration currently up and running inside a [NanoPi NEO2](https://www.friendlyarm.com/index.php?route=product/product&product_id=180) small board computer (SBC).

My NanoPI is currently running [Armbian Bionic](https://www.armbian.com/nanopi-neo-2/).

To install docker, please use the [convenience script](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-using-the-convenience-script).

To run, just enter the root folder and run:

```
docker-compose up -d
```

Feel free to send questions or PR's with improvements!

## Images

### Cloudflared

Cloudflare DNS resolution over an HTTPS endpoint.

* Image: [visibilityspots/cloudflared](https://hub.docker.com/r/visibilityspots/cloudflared)
* Tag: arm64

### Pi-hole

The Pi-hole® is a DNS sinkhole that protects your devices from unwanted content, without installing any client-side software.

* Image: [pihole/pihole](https://hub.docker.com/r/pihole/pihole)

### Nginx

Nginx (pronounced "engine-x") is an open source reverse proxy server for HTTP, HTTPS, SMTP, POP3, and IMAP protocols, as well as a load balancer, HTTP cache, and a web server (origin server).

* Image: [arm64v8/nginx](https://hub.docker.com/r/arm64v8/nginx)

### Home Assistant

Home Assistant is an open source home automation tool that puts local control and privacy first.

* Image: [homeassistant/aarch64-homeassistant](https://hub.docker.com/r/homeassistant/aarch64-homeassistant)

### Node-RED

Node-RED is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.

* Image: (local build)

### Eclipse Mosquitto

Eclipse Mosquitto is an open source implementation of a server for version 3.1 and 3.1.1 of the MQTT protocol.

* Image: [arm64v8/eclipse-mosquitto](https://hub.docker.com/r/arm64v8/eclipse-mosquitto)

### Zigbee2Mqtt

Zigbee2Mqtt allows you to use your Zigbee devices without the vendors bridge or gateway.

* Image: [koenkk/zigbee2mqtt](https://hub.docker.com/r/koenkk/zigbee2mqtt)
* Tag: arm64v8

### Portainer

Build and manage your Docker environments with ease today.

* Image: [portainer/portainer](https://hub.docker.com/r/portainer/portainer)
