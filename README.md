# bloodhound
Install and start a BloodHound CE with docker

## Install Docker and Docker Compose

$ sudo apt install docker.io -y 

$ sudo apt install docker-compose -y

## Start Docker Service

$ sudo service docker start

## Create and access the directory for download compose file

$ mkdir bloodhound

$ cd bloodhound

## Download Compose file

$ wget https://github.com/thiagosmith/bloodhound/blob/main/docker-compose.yml

## Up BloodHound

$ sudo docker-compose up

## Note: 
The first time you use the app, the password is generated using a hash displayed on the terminal. Copy the hash to log in for the first time using the admin user. After logging in, change the password to a strong one.

Source link docker-compose.yml: https://raw.githubusercontent.com/SpecterOps/bloodhound/main/examples/docker-compose/docker-compose.yml
