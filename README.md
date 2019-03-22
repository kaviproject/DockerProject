# DockerProject
important URLS to learn DOCKER<br/>

https://www.youtube.com/watch?v=wi-MGFhrad0


How to install Docker on Linux

Agenda:
Prerequisites<br/>
Connect to Linux<br/>
Install Docker<br/>
Start Docker<br/>
Stop Docker
Uninstall Docker


Prerequisite
OS should be 64 bit
Linux kernel ver 3.10 or greater

command to check : uname -r

STEP 1 - Connect to Linux system

STEP 2 - Install DOCKER
sudo yum -y update
sudo yum install -y docker

docker
docker --version

STEP 3 - start DOCKER
sudo service docker start
sudo usermod -a -G docker "user"

docker info

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
