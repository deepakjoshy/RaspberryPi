# RaspberryPi

## Guide for begninger's to setup Raspberry Pi

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



