# Docker Commands Cheat Sheet

### Docker Installation Instructions

#### 1.  Install Docker Desktop on Windows/Mac 
   - Download Docker Desktop from [Docker Hub](https://www.docker.com/products/docker-desktop) and follow the installation instructions for your operating system.

#### 2. Install Docker Engine on Other Linux 
   - Follow the instructions for your Linux distribution on [Docker's official documentation](https://docs.docker.com/engine/install/).

#### 3. Install docker into ubuntu machine 
   - **sudo apt-get update** : Update the package
   - **sudo apt-get install apt-transport-https ca-certificates curl software-properties-common** : Install required packages to allow apt to use a repository over HTTPS
   - **curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -** : Add Docker's official GPG key
   - **sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"** : Set up the stable Docker repository
   - **sudo apt-get update** : Update the package index again
   - **sudo apt-get install docker-ce** : Install Docker Community Edition (CE)
   - **sudo docker run hello-world** : Verify that Docker is installed correctly by running the hello-world container
   - **sudo usermod -aG docker $USER** : Add your user to the Docker group to run Docker commands without sudo
> Note : Logout and log back in or restart your system for the changes to take effect.

---    

### Basic Docker Commands

- **sudo docker run \<image>** : Run a container from an image.
- **sudo docker ps**: List running containers.
- **sudo docker ps -a**: List all containers (including stopped ones).
- **sudo docker images**: List all images on your system.
- **sudo docker pull \<image>**: Download an image from Docker Hub.
- **sudo docker build \<path/to/Dockerfile>**: Build an image from a Dockerfile.
---
### Container Management

- **docker start \<container>**: Start a stopped container.
- **docker stop \<container>**: Stop a running container.
- **docker restart \<container>**: Restart a container.
- **docker rm \<container>**: Remove a container.
- **docker rmi \<image>**: Remove an image.
---
### Docker Networking

- **docker network ls**: List Docker networks.
- **docker network create \<network>**: Create a Docker network.
- **docker network inspect \<network>**: Inspect a Docker network.
- **docker network connect \<network> \<container>**: Connect a container to a network.
---
### Docker Volumes

- **docker volume ls**: List Docker volumes.
- **docker volume create \<volume>**: Create a Docker volume.
- **docker volume inspect \<volume>**: Inspect a Docker volume.
- **docker volume rm \<volume>**: Remove a Docker volume.
---
### Docker Compose (Advanced)

- **docker-compose up**: Start services defined in a Docker Compose file.
- **docker-compose down**: Stop and remove containers defined in a Docker Compose file.
- **docker-compose build**: Build or rebuild services defined in a Docker Compose file.
- **docker-compose logs**: View output from services defined in a Docker Compose file.
---
### Docker Swarm (Advanced)

- **docker swarm init**: Initialize a Docker Swarm.
- **docker swarm join**: Join a Docker Swarm as a worker or manager node.
- **docker service create**: Create a service in a Docker Swarm.
- **docker node ls**: List nodes in a Docker Swarm.

---

Feel free to add or modify commands based on your needs and preferences.

