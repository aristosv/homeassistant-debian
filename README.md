# homeassistant-debian
Home Assistant installation on Debian

Run the command below on a clean, minimal installation of Debian Buster.
```
bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/aristosv/homeassistant-debian/master/hadebian)
```
It will install Home Assistant, including Hass.io in a containerized environment.

After the installation, this is how you can access the web apps:
```
Name: home assistant
Usage: home automation bridge
URL: http://<your_server_ip_here>:8123
```
```
Name: portainer
Usage: docker container management
URL: http://<your_server_ip_here>:9000
```
