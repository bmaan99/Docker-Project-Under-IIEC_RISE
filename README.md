# Docker-Project-Under-IIEC_RISE
This is my project created for docker training that I have completed last month. The training was given by Mr.Vimal Daga Sir. It has been an amazing experience to train under sir. Linkedin profile of sir https://www.linkedin.com/in/vimaldaga/. I have made a nextcloud project which can be accessed within the computer but if we have a public IP then we can access it from any computer in the world.
You can also learn to watch these lectures from youtube because these are free and open to everyone which is a great thing about this initiative. Youtube Link:: https://www.youtube.com/playlist?list=PLAi9X1uG6jZ30QGz7FZ55A27jPeY8EwkE

##What is Next Cloud?
Nextcloud is a suite of client-server software for creating and using file hosting services. Nextcloud is free and open-source, which means that anyone is allowed to install and operate it on their own private server devices.

Nextcloud application functionally is similar to Dropbox, Office 365 or Google Drive, but can be used on home-local computers or for off-premises file storage hosting. Office functionality is limited to x86/x64 based servers as OnlyOffice does not support ARM processors. In contrast to proprietary services, open architecture enables users to have full control of their data. You can learn more about the next cloud from their website: nextcloud.com

## Pre-configuration needed:
* I am using **RHEL 8** and  I have also installed Docker Software on it. You can use any Operating system but inside your Operating System, you must have docker installed and its docker-compose software.
After you have installed the docker you have to start docker services which are different for every Operating System

* Starting the docker:
  **For RHEL 8 or CentOS** Use command `systemctl start docker` in your Linux terminal to start Docker Service.
  **For other Operating Systems** Use `sudo service docker start` in your Linux terminal to start Docker Service.
  One of the above commands will work according to your operating system.
  
## Downloading required images for the project:
This is very simple you can directly download from your terminal without going into the browser. You can download it here or docker will download it when you run the docker-compose file

* Pulling MySQL Image:
  * Use `docker pull mysql:5.6` to download the **mysql version 5.6** image to use as a database server.
  * To know more about MySQL Image go to this page: https://hub.docker.com/_/mysql
* Pulling Nextcloud Image:
  * Use `docker pull nextcloud:latest` to download the Nextcloud Image in which the apache server is already preconfigured.
  * To know more about Nextcloud Image go to this page: https://hub.docker.com/_/nextcloud
  
## Docker-Compose:
  * Before using Docker-Compose you should install the software. For reference go to this website: https://docs.docker.com/compose/install/
  * You can create and edit this file using vim editor. For that use `vim docker-compose.yml`.
  * After installing it you can use `docker-compose up` command in the directory where you have saved the docker_compose.yml file and start using next cloud services 
