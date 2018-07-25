# DOCKER 

@fa[docker]


A platform to develop, deploy, and run applications using Linux containers.

---

### The Latest Hype Beast
@ul
- Flexible: Almost anything can be containerized
- Lightweight: Containers leverage and share the host kernel
- Portable: You can build locally, deploy to the cloud, and run anywhere
- Interchangeable: You can deploy updates and upgrades on-the-fly.
- Scalable: You can increase and automatically distribute container replicas
- Stackable: You can stack services vertically and on-the-fly
@ulend
---

### Lets install Docker
@ul
- sudo apt install apt-transport-https ca-certificates curl software-properties-common
- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
- sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
- sudo apt-get update
- sudo apt-get install docker-ce
- sudo usermod -aG docker gibl3t
- reboot
@ulend
---

### Our First Container

- docker run hello-world
```
Hello from Docker!
This message shows that your installation appears to be working correctly.

Blah Blah

$ docker run -it ubuntu bash
```

---

### Basic Commands
@ul
- docker ps     :   List running containers (use -a for all)
- docker images :   List all present images
- docker pull   :   Pull an image
- docker run    :   Run a process in a new container
- docker stop   :   Stop a container
- docker start  :   rm -rf ~/*
@ulend

---

### Basic Web Server
@ul
- docker pull nginx
- docker run --name docker-nginx -p 80:80 -d nginx
- docker ps
- Profit $$$
@ulend
---

# Thank.
