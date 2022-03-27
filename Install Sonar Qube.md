## To install Sonar Qube we need
1.ubuntu 
2.docker 

## Step 1.

### First we need to install docker 
$ sudo apt-get remove docker docker-engine docker.io
$ sudo apt-get update
$ sudp apt install docker.io
$ sudo snap install docker

## Step 2.
# Running SonarQube on Docker
$ docker run -d --name sonarqube -p 9000:9000 -p 9092:9092 sonarqube

## Putll the letest sonarqube images
$ git clone https://github.com/HoussemDellai/WebAppWithDatabaseDemo