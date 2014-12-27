# Myzsh Docker
A docker enhancement module for myzsh

#Installation
```
myzsh remote add http://github.com/myzsh/myzsh-docker
```

#Additions
* Adds a set of autocompletions for docker
* Handles some trivial boot2docker things for OS X users
* `docker dev <image_name>` - puts you in a docker container of <image_name> with the current working directory mapped in
* `docker clean` - clears out those pesky unnamed containers and images that litter your environment
