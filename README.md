# Myzsh Docker
A docker enhancement module for myzsh.  Adds custom commands and autocompletions.

#Installation
```
myzsh remote add http://github.com/myzsh/myzsh-docker
```

#Commands
* `docker clean` - Clean up images or containers, or both
* `docker describe` - Describe how a container was started
* `docker dev` - Run /bin/bash in an image with $PWD mapped in
* `docker down` - Stop boot2docker vm with docker-machine
* `docekr enter` - Run interactive prompt with /bin/bash by default, or passed in command
* `docker env` - Setup boot2docker env variables
* `docker init` - Setup boot2docker with docker-machine
* `docker ip` - Get the IP of a container
* `docker nuke` - Kill all running containers
* `docker socket` - Run a proxy socket on /tmp/proxysocket.sock
* `docker shove` - Use save and load to push an image into another daemon over ssh
* `docker up` - Start boot2docker vm with docker-machine
* `docker upgrade` - Upgrade boot2docker vm to latest version
