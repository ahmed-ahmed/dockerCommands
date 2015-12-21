# Docker Commands

### installing Docker 

```sh 
apt-get install docker.io               #on ubunto
yum install docker                      # redhat/centOS
```

### information
```sh 
docker -v                               #basic information 
docker version                          # more detailed informations  
docker info                             # no of containers and other informatins
```

### basic commands 

```sh
docker run -it centos /bin/bash     # creating a centOS container -it: interactive and start the bash 




docker start 27eafccb290           # start a container with its short container id: 27eafccb290
docker attach 27eafccb290          # attach the command line to the container 27eafccb290


/var/lib/docker/aufs/diff           # where container's files exists there is a folder for each container, the folder name = container's name
