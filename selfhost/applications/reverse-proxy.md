---
id: 20210328204734
title: "Setup a reverse-proxy"
created: 2021-01-14
keywords:
  - selfhosting
  - linux
  - networking
---
# Reverse proxy
*The thing that makes app.domain.tld resolve to your application* 

there are a number of options like caddy, nginx and ofc apache.

I chose npm because nginx ist fast and the gui makes it easy to set up and maintain everything.


## Nginx Proxy Manager
*Web Server, Reverse Proxy*

Install Video: https://www.youtube.com/watch?v=P3imFC7GSr0
Install Guide: https://nginxproxymanager.com/setup/

### Connect the rev-proxy to your container(s)
examples:

- sudo docker network connect portainer_default nginxproxymanager_app_1
- sudo docker network connect rocketchat_default nginxproxymanager_app_1
- sudo docker network connect azuracast_default nginxproxymanager_app_1

I think you get the idea, right?