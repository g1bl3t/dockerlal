# DOCKER 

@fa[docker]

A platform to develop, deploy, and run applications using Linux containers.

---

### The Latest Hype Beast

- Flexible: Almost anything can be containerized
- Lightweight: Containers leverage and share the host kernel
- Portable: You can build locally, deploy to the cloud, and run anywhere
- Interchangeable: You can deploy updates and upgrades on-the-fly.
- Scalable: You can increase and automatically distribute container replicas
- Stackable: You can stack services vertically and on-the-fly
---

### Lets install Docker
- sudo apt install apt-transport-https ca-certificates curl software-properties-common
- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
- sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian $(lsb_release -cs) stable"
- sudo apt-get update
- sudo apt-get install docker-ce
- sudo usermod -aG docker gibl3t
- reboot

---

### Our First Container

- docker run hello-world
```
Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash
```

---

### Basic Commands

- docker ps     :   List running containers (use -a for all)
- docker images :   List all present images


---

### Basic Web Server

- docker pull nginx
- docker run --name docker-nginx -p 80:80 -d nginx
- docker ps
- Profit $$$

---

# Thank.
