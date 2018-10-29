# Docker utils
_Personal docker utils_


## Misc

Delete all the images <br>
`sudo docker rmi $(sudo docker images -q)`

Delete all the containers <br>
`sudo docker rm $(sudo docker ps -a -q)`
