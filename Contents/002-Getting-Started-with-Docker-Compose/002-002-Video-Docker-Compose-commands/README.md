# [Docker Compose commands](https://www.linkedin.com/learning/learning-docker-compose-simplified-multi-container-application-management/docker-compose-commands)
```bash
docker compose --project-directory /run/media/ramumsrk/ata_1_0_TiB/LinkedIn-Learning/Learning-Docker-Compose-Simplified-Multi-Container-Application-Management-by-Pawel-Piwosz/Contents/002-Getting-Started-with-Docker-Compose/002-002-Video-Docker-Compose-commands up
```
#### Command output
```bash
WARN[0000] /run/media/ramumsrk/ata_1_0_TiB/LinkedIn-Learning/Learning-Docker-Compose-Simplified-Multi-Container-Application-Management-by-Pawel-Piwosz/Contents/002-Getting-Started-with-Docker-Compose/002-002-Video-Docker-Compose-commands/docker-compose.yml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion 
[+] up 2/2
 ✔ Network 002-002-video-docker-compose-commands_default Created                                                                                                                                                                                                                  0.2s
 ✔ Container first-hello-world-container                 Created                                                                                                                                                                                                                  0.7s
Attaching to first-hello-world-container
first-hello-world-container  | 
first-hello-world-container  | Hello from Docker!
first-hello-world-container  | This message shows that your installation appears to be working correctly.
first-hello-world-container  | 
first-hello-world-container  | To generate this message, Docker took the following steps:
first-hello-world-container  |  1. The Docker client contacted the Docker daemon.
first-hello-world-container  |  2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
first-hello-world-container  |     (amd64)
first-hello-world-container  |  3. The Docker daemon created a new container from that image which runs the
first-hello-world-container  |     executable that produces the output you are currently reading.
first-hello-world-container  |  4. The Docker daemon streamed that output to the Docker client, which sent it
first-hello-world-container  |     to your terminal.
first-hello-world-container  | 
first-hello-world-container  | To try something more ambitious, you can run an Ubuntu container with:
first-hello-world-container  |  $ docker run -it ubuntu bash
first-hello-world-container  | 
first-hello-world-container  | Share images, automate workflows, and more with a free Docker ID:
first-hello-world-container  |  https://hub.docker.com/
first-hello-world-container  | 
first-hello-world-container  | For more examples and ideas, visit:
first-hello-world-container  |  https://docs.docker.com/get-started/
first-hello-world-container  | 
first-hello-world-container exited with code 0
```
#### Command
```bash
docker network list
```
#### Command output
```bash
NETWORK ID     NAME                                            DRIVER    SCOPE
d166720feea7   002-002-video-docker-compose-commands_default   bridge    local
9c0796b7ad5c   bridge                                          bridge    local
0a38c4c818cb   host                                            host      local
7f50aea1189f   none                                            null      local
```