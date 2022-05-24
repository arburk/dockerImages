# Dockerfiles

Serves as repository for different dockerfiles.

## [dind-jenkins-without-podman](./dind-jenkins-without-podman/readme.md)

In case of using [testcontainers](https://www.testcontainers.org/) in CI build using Maven and Jenkins but
Podman is only available in version<3, this container will encapsulate the build providing required infrastructure.

## [pi-hole](./pi-hole/docker-compose.yml)

> [Pi-hole](https://pi-hole.net/) is a Linux network-level advertisement and Internet tracker blocking application which
> acts as a DNS sinkhole
> and optionally a DHCP server, intended for use on a private network. It is designed for low-power embedded devices
> with network capability, such as the Raspberry Pi, but can be installed on any Linux machine.
>
>Pi-hole has the ability to block traditional website advertisements as well as advertisements in unconventional places,
> such as smart TVs and mobile operating system advertisements.

https://en.wikipedia.org/wiki/Pi-hole

## Resources

- [Alpine linux CDN](https://dl-cdn.alpinelinux.org/alpine/v3.14/) for apk install packages
