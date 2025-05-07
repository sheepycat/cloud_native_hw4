# cloud_native_hw4
* Docker Hub: [sheepycat/2025cloud](https://hub.docker.com/r/sheepycat/2025cloud/tags)

### Clone Repo
```bash
git clone https://github.com/sheepycat/cloud_native_hw4.git
```

* Use docker-compose.yml to help building and running. Settings can be modified in the file. (binding port, docker hub repo, binding dir...etc)
### build image from local
```bash
cd local

# This will automatically build the image using the Dockerfile and run the container：
sudo docker-compose up -d

```
### Use Pre-Built image from Docker Hub
```bash
cd built

# This will pull the pre-built image from Docker Hub and run the container：
sudo docker-compose up -d
```
