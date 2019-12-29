Docker is a tool for create and run containers. Docker was released by Solomon Hykes in 2013 under Apache License 2.0.

The main components of docker are:

- Daemon: (dockerd) listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes
- Client: (docker) is the primary way that many Docker users interact with Docker. When you use commands such as docker run, the client sends these commands to dockerd, which carries them out. The docker command uses the DockerAPI.
- Registry: Docker registry stores Docker images.

Docker is available in two editions:
- Community Edition (CE): for individual developers and small teams.
- Enterprise Edition (EE): for enterprise development and IT teams who run business critical applications in production at scale.
