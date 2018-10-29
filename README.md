# Docker utils
_Personal docker utils_


## Misc commands

Delete all the images <br>
`sudo docker rmi $(sudo docker images -q)`

Delete all the containers <br>
`sudo docker rm $(sudo docker ps -a -q)`

## Bash scripts (insert into .bashrc)
Starts container's bash running `docker-bash [CONTAINER ID]`
```
docker-bash() {
    sudo docker exec -i -t $1 /bin/bash
}
```