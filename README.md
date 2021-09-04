# RaspberryPi

## Guide for beginner's to setup Raspberry Pi Home Server

Install Raspberry Pi OS using Raspberry Pi Imager : <a href="https://downloads.raspberrypi.org/imager/imager_latest.exe">Windows</a>  |  <a href="https://downloads.raspberrypi.org/imager/imager_latest_amd64.deb">Ubuntu</a>

After booting raspberry pi for first time update the os with latest components.
```bash
sudo apt-get update
sudo apt-get upgrade
```

.

.
 
 
------------



###  GNU Wget
GNU Wget is a free software package for retrieving files using HTTP, HTTPS, FTP and FTPS, the most widely used Internet protocols. It is a non-interactive commandline tool, so it may easily be called from scripts, cron jobs, terminals without X-Windows support, etc.

```bash
sudo sh -c 'echo "deb http://ftp.au.debian.org/debian/ buster main non-free" > /etc/apt/sources.list.d/nonfree.list'
sudo apt update
sudo apt install
```

.

.
 
------------




## Webmin:
Webmin is excellent if you wish to have a web-based interface for system administration. It removes the need to manually edit configuration files and makes administration a lot easier.

Installation:

```bash
    wget http://prdownloads.sourceforge.net/webadmin/webmin_1.981_all.deb
    sudo dpkg --install webmin_1.981_all.deb

```

.

.
 
------------

## Plex Media Server  

Plex Media Server is a user-friendly way to store all your movies, shows, and other media in one place–and make it accessible from any device, whether you’re at home or on-the-go. If you’re looking for a no-headache way to watch your movies anywhere, this is it.

.

.

.

.

.

. 




------------

## Setting Up Mount Drive

It’s important to know that Raspbian lite currently does not automatically mount your drives. So you will need to either set it up manually or install the software package to have it automatically mount.

https://pimylifeup.com/raspberry-pi-mount-usb-drive/


.

.

.

.

.

------------

## Samba 

A Samba file server enables file sharing across different operating systems over a network. It lets you access your files in raspberry pi and share files with Windows and macOS users.

 <a href="https://pimylifeup.com/raspberry-pi-samba/">Setup Instructions</a>

.

.
```bash
    sudo apt-get update
    sudo apt-get upgrade 
    sudo apt-get install samba samba-common-bin


```
.

.

. 

------------

## Nextcloud

Nextcloud is a suite of client-server software for creating and using file hosting services. It is enterprise-ready with comprehensive support options. Being free and open-source software, anyone is allowed to install and operate it on their own private server devices.
 
 <a href="https://pimylifeup.com/raspberry-pi-nextcloud-server/">Setup Instructions</a>



.

.

.

.

.
 
------------
 


## Snap

What are Snap Packages?

Snaps are cross-distribution, dependency-free, and easy to install applications packaged with all their dependencies to run on all major Linux distributions. From a single build, a snap (application) will run on all supported Linux distributions on desktop, in the cloud, and IoT. Supported distributions include Ubuntu, Debian, Fedora, Arch Linux, Manjaro, and CentOS/RHEL.

Snaps are secure – they are confined and sandboxed so that they do not compromise the entire system. They run under different confinement levels (which is the degree of isolation from the base system and each other). More notably, every snap has an interface carefully selected by the snap’s creator, based on the snap’s requirements, to provide access to specific system resources outside of their confinement such as network access, desktop access, and more.

Installation:

```bash
    $ sudo apt update
    $ sudo apt install snapd
    
    $ sudo reboot
    
    $ sudo snap install core 
```

.

.

.

------------
## Docker

Docker is a tool for creating, deploying, and running applications in containers. The software is popular among developers as it speeds up the development process and does not use a lot of resources.

Docker containers are lightweight, especially compared to virtual machines. This feature is especially valuable if you are a Raspberry Pi user.

If you need help installing Docker on your Raspberry Pi, read our step-by-step guide on how to install Docker on Raspberry Pi.


 <a href="https://phoenixnap.com/kb/docker-on-raspberry-pi">Setup Instructions</a>

.

.

.
