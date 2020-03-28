# Container

A random collection of docker-compose files I use to organise my containers.
Each folder contains a `docker-compose.yml` file. The private configuration of
each `docker-compose-yml` file is organized in a `.env` file. An example version
of the `env` is also provided.

To create a container `cd` next to its `docker-compose.yml` and run `sudo docker-compose up -d` 
To update a running container to exactly the same as above. Once the new container runs, prune dangling images with: `sudo docker image prune` 

## Jitsi Meet
A collaborative video and audio conference/chat system based on webrtc. See https://jitsi.org/jitsi-meet/ and https://github.com/jitsi/docker-jitsi-meet

## Lutscher
A combination of sonarr, radarr, transmission and jacket.
- https://sonarr.tv/
- https://hub.docker.com/r/linuxserver/sonarr/
- https://radarr.video/
- https://hub.docker.com/r/linuxserver/radarr/
- https://transmissionbt.com/
- https://hub.docker.com/r/linuxserver/transmission/
- https://github.com/Jackett/Jackett
- https://hub.docker.com/r/linuxserver/jackett/

## Nextcloud
Private cloud service. See https://nextcloud.com/ and https://github.com/nextcloud/docker

## Nginx Proxy Manager
GUI to manage web proxies with nginx. See
https://github.com/jlesage/docker-nginx-proxy-manager

## Portainer
Gui tool to organize docker container. See https://www.portainer.io/

## Plex
Video organisation platform. See https://www.plex.tv/ and
https://hub.docker.com/r/linuxserver/plex/

## Ocrmypdf
Container to automatically scan the content of an input folder for new pdf. On discovery of a new file, ocrmypdf is used to generate a searchable version of the same pdf and store in in output folder. See https://github.com/jbarlow83/OCRmyPDF
