# Dockerfiles
Serves as repository for different dockerfiles.

## [dind-jenkins-without-podman](./dind-jenkins-without-podman/readme.md)
In case of using [testcontainers](https://www.testcontainers.org/) in CI build using Maven and Jenkins but 
Podman is only available in version<3, this container will encapsulate the build providing required infrastructure. 

## Resources
- [Alpine linux CDN](https://dl-cdn.alpinelinux.org/alpine/v3.14/) for apk install packages
