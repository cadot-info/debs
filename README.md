# debs form cadot.info Factory

Install deb by `sudo dpkg -i ...deb`
Install all by `sudo dpkg -i *.deb`

## shtodeb
For create deb from bash script
Follow instructions
-r option for remove directory generate and mv deb in current directory


## gcp 
git and commit with auto tags for package.json
`git -i` for init 

## runsite
Create Docker-compose.yml if don't exist with the actual directory and return port for http://localhost:...
I use symfony5 docker image and port 80

## local-update-db-public
Update local db and public from distant server.
He activate maintenace mode.
He use .env parameters
```bash
SERVER_CONNECT=user@ip or name
SERVER_DIR=/home/.../...
```
## server-update-yarn-composer
Update distant by github, composer and yarn from .env and use maintenance mode
```bash
SERVER_CONNECT=user@ip or name
SERVER_DIR=/home/.../...
```
## server-run-command
run a command in the distant server from .env

`server-run-command "ls"`

```bash
SERVER_CONNECT=user@ip or name
SERVER_DIR=/home/.../...
```
## docker-kill-all
kill all docker and remove
`docker-kill-all`

## docker-kill
kill docker and remove
`docker-kill nameOfDocker`
