# Chord Implementation on Docker
**Installing Docker Compose (Linux):**
1. Run this command to download Docker Compose:
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.25.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```
2. Apply executable permissions:
```
sudo chmod +x /usr/local/bin/docker-compose
```
*Installation instructions from [Docker Compose](https://docs.docker.com/compose/install/)*

**Setting up nodes:**
Run the compose file:
```
docker-compose up -d --scale node=5
```
This create 1 root node, and 5 other nodes. 
