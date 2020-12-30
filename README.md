# Syslog-relay

### Prerequisites
Install git

Install docker - Dockerhttps://docs.docker.com/install/

Install docker-composer - https://docs.docker.com/compose/install/

## Quick Start

- Clone de proyect
- ```cd syslog-relay```
- copy the configuration file ```cp config/syslog-ng.conf.demo config/syslog-ng.conf```
- Edit the configuration file ```nano config/syslog-ng.conf```


### Architecture
The example file shows how to configure a remote output server, but you can configure N servers and additionally save it in local files.

![screenshots](https://i.imgur.com/tjiKjJ5.png)

