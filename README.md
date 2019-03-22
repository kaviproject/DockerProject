# DockerProject
important URLS to learn DOCKER<br/>

https://www.youtube.com/watch?v=wi-MGFhrad0


How to install Docker on Linux

Agenda:
Prerequisites<br/>
Connect to Linux<br/>
Install Docker<br/>
Start Docker<br/>
Stop Docker<br/>
Uninstall Docker<br/>


Prerequisite
OS should be 64 bit<br/>
Linux kernel ver 3.10 or greater<br/>

command to check : uname -r<br/>

STEP 1 - Connect to Linux system<br/>

STEP 2 - Install DOCKER<br/>
sudo yum -y update<br/>
sudo yum install -y docker<br/>

docker
docker --version<br/>

STEP 3 - start DOCKER<br/>
sudo service docker start<br/>
sudo usermod -a -G docker "user"<br/>

docker info5<br/>55

docker run hello-world : to run hello-world image

docker images : to get list of images present locally

docker ps : to get list of running containers

docker ps -a .  : to get list of all containers

STEP 4 - stop DOCKER
sudo service docker stop
uninstall DOCKER
sudo yum remove docker

HELPFUL TIPS
You can visit - https://get.docker.com/
for more installation related help

To install docker from binaries
https://docs.docker.com/engine/instal...

Installation steps for amazon ec2
http://docs.aws.amazon.com/AmazonECS/...


References:

Linux free instance - https://aws.amazon.com/free/

Docker Manuals - https://docs.docker.com/manuals/

https://get.docker.com/

https://docs.docker.com/engine/instal...

http://docs.aws.amazon.com/AmazonECS/...
____________________________________________________________

_____________________________________________________________

#DockerOnLinux #DockerInstallation #HowToInstallDocker #DockerTutorials #DockerTraining #DevOpsTools #DevOpsTraining #DockerCommands #DockerForBeginners

DOCKER PLAYLIST
https://www.youtube.com/playlist?list...


Interview Questions
Basic
: docker version
: docker -v
: docker info
: docker --help
: docker login
————————————
Images
: docker images
: docker pull
: docker rmi
————————————
Containers
: docker ps
: docker run
: docker start
: docker stop
————————————
System
: docker stats
: docker system df
: docker system prune
