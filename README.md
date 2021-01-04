# Home Lab Configuration and Layout

To start, this homelab is nothing close to what you would see online in communities such as r/homelab and things like that. Currently, it consists of two Raspberry Pi 4 (4GB). The details of the hosts are below.

## Infrastructure
* Hostname: Dockerhost01
    * OS: Ubuntu Server 20.04 LTS
    * IP Address: 192.168.1.15/24
    * Services hosted:
        * Portainer
        * Pihole
        * Ubiquiti Unifi Controller
    * Hardware: Raspberry Pi 4 (4GB)

* Hostname: Dockerhost02
    * OS: Ubuntu Server 20.04 LTS
    * IP Address: 192.168.1.20/24
    * Hosted Services:
        * Portainer
        * Home Assistant
        * FreshRSS
    * Hardware: Raspberry Pi 4 (4GB)
