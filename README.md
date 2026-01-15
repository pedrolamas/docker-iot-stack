# Docker IoT Stack

[![Project Maintenance](https://img.shields.io/maintenance/yes/2026.svg)](https://github.com/pedrolamas/nanopineo2-docker-config 'GitHub Repository')
[![License](https://img.shields.io/github/license/pedrolamas/nanopineo2-docker-config.svg)](https://github.com/pedrolamas/nanopineo2-docker-config/blob/master/LICENSE 'License')

[![Follow pedrolamas.com on Bluesky](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fpublic.api.bsky.app%2Fxrpc%2Fapp.bsky.actor.getProfile%2F%3Factor%3Dpedrolamas.com&query=%24.followersCount&style=social&logo=bluesky&label=Follow%20%40pedrolamas.com)](https://bsky.app/profile/pedrolamas.com)
[![Follow pedrolamas on Mastodon](https://img.shields.io/mastodon/follow/109365776481898704?label=Follow%20@pedrolamas%20on%20Mastodon&domain=https%3A%2F%2Fhachyderm.io&style=social)](https://hachyderm.io/@pedrolamas)

This is my personal Docker IoT Stack configuration, currently up and running inside a [NanoPi M4V2](https://www.friendlyarm.com/index.php?route=product/product&product_id=180) small board computer (SBC) with a Sabrent 256GB Rocket NVMe PCIe M.2 2280 SSD.

The NanoPI is running the latest [Armbian OS](https://www.armbian.com/nanopi-m4-v2/).

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

* Image: [ghcr.io/home-assistant/home-assistant](https://github.com/home-assistant/core/pkgs/container/home-assistant)

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

* Image: [grafana/grafana](https://hub.docker.com/r/grafana/grafana)

### ESPHome

ESPHome is a system to control your ESP8266/ESP32 by simple yet powerful configuration files and control them remotely through Home Automation systems.

* Image: [ghcr.io/esphome/esphome](https://github.com/esphome/esphome/pkgs/container/esphome)

### ACME.sh

An ACME protocol client written purely in Shell (Unix shell) language.

* Image: [neilpang/acme.sh](https://hub.docker.com/r/neilpang/acme.sh)

### code-server

Run VS Code on any machine anywhere and access it through the browser.

* Image: [codercom/code-server](https://hub.docker.com/r/codercom/code-server)

### Portainer

Build and manage your Docker environments with ease today.

* Image: [portainer/portainer](https://hub.docker.com/r/portainer/portainer)

### Fluidd

Fluidd is a lightweight & responsive user interface for Klipper, the 3D printer firmware.

* Image: [ghcr.io/fluidd-core/fluidd:latest-develop](https://github.com/fluidd-core/fluidd/pkgs/container/fluidd)

### Mainsail

Mainsail makes Klipper more accessible by adding a lightweight, responsive web user interface, centred around an intuitive and consistent design philosophy.

* Image: [ghcr.io/pedrolamas/docker-mainsail:latest-dev](https://github.com/pedrolamas/docker-mainsail/pkgs/container/docker-mainsail)

### Spoolman

Spoolman is a web service that helps you keep track of your filament spools and how they are being used.

* Image: [ghcr.io/donkie/spoolman](https://github.com/donkie/spoolman/pkgs/container/spoolman)

### adsb-ultrafeeder

adsb-ultrafeeder™ is an ADS-B data collector container.

* Image: [ghcr.io/sdr-enthusiasts/docker-adsb-ultrafeeder](https://github.com/sdr-enthusiasts/docker-adsb-ultrafeeder/pkgs/container/docker-adsb-ultrafeeder)

### docker-flightradar24

Docker container running FlightRadar24's fr24feed. Designed to work in tandem with sdr-enthusiasts/docker-adsb-ultrafeeder.

* Image: [ghcr.io/sdr-enthusiasts/docker-flightradar24](https://github.com/sdr-enthusiasts/docker-flightradar24/pkgs/container/docker-flightradar24)

### docker-opensky-network

Docker container running OpenSky Network's's opensky-feeder. Designed to work in tandem with sdr-enthusiasts/docker-adsb-ultrafeeder.

* Image: [ghcr.io/sdr-enthusiasts/docker-opensky-network](https://github.com/sdr-enthusiasts/docker-opensky-network/pkgs/container/docker-opensky-network)

### Wireguard

WireGuard® is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography.

* Image: [linuxserver/wireguard](https://hub.docker.com/r/linuxserver/wireguard)

### Transmission

Transmission is a cross-platform BitTorrent client.

* Image: [linuxserver/transmission](https://hub.docker.com/r/linuxserver/transmission)

### Jackett

Jackett works as a proxy server: it translates queries from apps into tracker-site-specific http queries, parses the html response, then sends results back to the requesting software.

* Image: [linuxserver/jackett](https://hub.docker.com/r/linuxserver/jackett)

### Sonarr

Sonarr is a PVR for Usenet and BitTorrent users.

* Image: [linuxserver/sonarr](https://hub.docker.com/r/linuxserver/sonarr)

### Radarr

Radarr is an independent fork of Sonarr reworked for automatically downloading movies via Usenet and BitTorrent.

* Image: [linuxserver/radarr](https://hub.docker.com/r/linuxserver/radarr)

### FlareSolverr

FlareSolverr is a proxy server to bypass Cloudflare and DDoS-GUARD protection.

* Image: [ghcr.io/flaresolverr/flaresolverr](https://github.com/FlareSolverr/FlareSolverr/pkgs/container/flaresolverr)

## Support my work

A lot of time and effort goes into the development of this and other open-source projects.

If you find this project valuable, please consider supporting my work by making a donation.

[![Donate on Paypal](https://img.shields.io/badge/donate-paypal-blue.svg)](https://paypal.me/pedrolamas 'Donate on Paypal')
[![Buy me a coffee](https://img.shields.io/badge/buy%20me%20a%20coffee-kofi-blue.svg)](https://ko-fi.com/pedrolamas 'Buy me a coffee')
[![Support me on Patreon](https://img.shields.io/badge/join-patreon-blue.svg)](https://www.patreon.com/pedrolamas 'Support me on Patreon')
[![Sponsor me on GitHub](https://img.shields.io/github/sponsors/pedrolamas.svg?label=github%20sponsors)](https://github.com/sponsors/pedrolamas 'Sponsor me on GitHub')

Thank you for your generosity and support! 🙏

## License

MIT
