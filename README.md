# Devops-Studies

    Cloud, Docker and more.

## Docker

### Common commands

`docker ps` - list all containers that are current running
`docker ps -a` - list all containers (running or not)
`docker images` - list all images
`docker logs -f <container_name>` - view all logs of a container
`docker info` - verify the specs of docker (ram, os, etc)
`docker inspect <container_name>` - view a json like file with all the configuration of the container (args, envs, etc)
`docker stats` - verify the current usage (ram, cpu, etc) of all running containers
`docker run <container_name> <image_name>` - create and run an container based on a image
`docker exec <container_name>` - execute a command in a container
`docker exec -it <container_name> bash` - open a console inside the container
`docker start <container_name>` - start the container (don't create like run)
`docker stop <container_name>` - stop the container
`docker restart <container_name>` - stop and start the container
`docker rm <container_name>` - remove a container (can't be running)
`docker rmi <image_name>` - remove a image (can't be used by any container)
`docker-compose up` - start a docker-compose file in current directory
`docker-compose -f path/docker-compose.yaml up` - start a docker-compose file in current directory
`docker-compose up --build` - start a docker-compose file in current directory and build it again
`docker-compose down` - stop the docker-compose daemon

### General concepts

#### Image

#### Container

#### Networks

#### Volumes

### YAML

#### Basic key value

    Atributes the value `someone` to name

    ```yaml
    name: someone
    ```

#### key value of key value

    both elements location and router are part of datacenter item.

    ```yaml
    datacenter:
      location: São Paulo
      router: 42
    ```

#### Lists

    Atributes a list to the key roles with the values ['web', 'dns']

    ```yaml
    roles:
      - web
      - dns
    ```

## References

### Free

* [Docker cheat sheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf)
* [Docker beginner](https://www.youtube.com/watch?v=pg19Z8LL06w)
* [Docker complete course](https://www.youtube.com/watch?v=3c-iBn73dDE)
* [DevOps Tools](https://www.youtube.com/playlist?list=PLy7NrYWoggjxKDRWLqkd4Kbt84XEerHhB)

### Paid

* [Docker course Udemy](https://www.udemy.com/course/docker-essencial-para-o-desenvolvedor)
* [Infra as code Alura](https://cursos.alura.com.br/formacao-infraestrutura-codigo)
