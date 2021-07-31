# RaspberryPi

## Guide for beginner's to setup Raspberry Pi Home Server

Install Raspberry Pi OS using Raspberry Pi Imager : <a href="https://downloads.raspberrypi.org/imager/imager_latest.exe">Windows</a>  |  <a href="https://downloads.raspberrypi.org/imager/imager_latest_amd64.deb">Ubuntu</a>

After booting raspberry pi for first time update the os with latest components.
```bash
sudo apt-get update
sudo apt-get upgrade
```

------------



###  GNU Wget
GNU Wget is a free software package for retrieving files using HTTP, HTTPS, FTP and FTPS, the most widely used Internet protocols. It is a non-interactive commandline tool, so it may easily be called from scripts, cron jobs, terminals without X-Windows support, etc.

```bash
sudo sh -c 'echo "deb http://ftp.au.debian.org/debian/ buster main non-free" > /etc/apt/sources.list.d/nonfree.list'
sudo apt update
sudo apt install
```

------------




## Webmin:
Webmin is excellent if you wish to have a web-based interface for system administration. It removes the need to manually edit configuration files and makes administration a lot easier.

Installation:

```bash
    wget -qO - http://www.webmin.com/jcameron-key.asc | sudo apt-key add -
    sudo sh -c 'echo "deb http://download.webmin.com/download/repository sarge contrib" > /etc/apt/sources.list.d/webmin.list'
    sudo apt update
    sudo apt install webmin
```

------------

## Plex Media Server  

Plex Media Server is a user-friendly way to store all your movies, shows, and other media in one place–and make it accessible from any device, whether you’re at home or on-the-go. If you’re looking for a no-headache way to watch your movies anywhere, this is it.

.

.

.

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

.

.

.

.

.

.

.

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

.

.

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
