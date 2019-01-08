# Docker Container setup

- Ruby 2.5.3
- Rails 5.2.2
- MYSQL 5.7.24

This repo is meant for building a simple container that has the most basic requirements for learning Ruby and Ruby on Rails

### Download Docker

Only required if you don't have docker already installed on your computer. [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

### Installation

1. Download this repo, unzip it, and place it in your working directory
2. Run `docker-compose up -d` this will build the container and run it in the background

That's it!

### Log in

Accessing the container is easy, use the command `docker exec -it img240 /bin/bash`

### MYSQL

In order to access your container's MYSQL server you'll need the following credentials:

```
host: 127.0.0.1
user: root 
pass: root
```

