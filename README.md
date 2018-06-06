# docker-php-web

This is a tutorial how to start with dokcer compose.

### readmore

https://docs.docker.com/compose

# How to setup

## 1. git clone 

```git clone https://github.com/ppongsak/docker-php-web.git```

clone in the same your project directory

## 2. edit yml file

```cd docker-php-web```

```vim docker-compose.yml```

### edit

image
container name
ports ex. localhost:8001 is a docker port but default is 8080
volumns (mapping your project)
working dir

then save

## 3. Run

```docker-compose up -d```

## 4. Checking 

check container is created

```docker ps```

## 5. Bash

if need to bash into container 

```docker exec -it <container-name> bash```

## 6. http request

test request to project

```ex. localhost:8001```


