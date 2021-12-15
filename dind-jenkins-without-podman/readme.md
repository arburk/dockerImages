# dind-jenkins-without-podman
In case of using [testcontainers](https://www.testcontainers.org/) in CI build using Maven and Jenkins but 
Podman is only available in version<3, this container will encapsulate the build providing required infrastructure. 

`docker build . -t arburk/dind-jenkins-without-podman`

__Further documentation:__
- https://www.testcontainers.org/supported_docker_environment/continuous_integration/dind_patterns/
- https://hub.docker.com/_/docker
