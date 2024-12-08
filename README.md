# Docker-rclone
Docker image to use rclone to run cron sync

## Description

Small docker image with [rclone](https://rclone.org/) built from scratch so it's as light as possible.

This image should be available (unless a problem happened on my side) for the following architectures :
 * amd64
 * armhf
 * arm64

I'm using a proper manifest so you can use the main tags directly (no need for amd64-X.X.X).

If you want to learn more about multi-architecture docker images, please read [my blog](https://blog.slucas.fr/series/multi-architecture-docker-image/)

## Usage

You can use this image as you would use the `rclone` binary.

```
docker run -it --rm seblucas/docker-rclone:latest --help
docker run -it --rm -v /var/opt/docker/rclone/.config:/.config seblucas/docker-rclone:latest ls remote:/mydir
```

If you need to sync files you can mount another volume wherever you want.

## License

This project is licensed under `GPLv3`.

# Easy Breezy AC

Easy Breezy AC is a family owned and operated company in the Tampa Bay area since 2009.  Easy Breezy AC serves Pinellas, Pasco, Hillsborough, and Hernando Counties.
Easy Breezy AC is a Paperless and Cloud-based HVAC company. Easy Breezy specializes in eco-friendly, high efficiency AC Repair, AC Service, AC Maintenance, and AC Installation. 

More trees and less pollution since 2009.
Life's Hard. Comfort's Not.
