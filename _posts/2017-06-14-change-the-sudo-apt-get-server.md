---
layout: post
published: false
title: Change the sudo apt-get server
---
## Change the sudo apt-get server

The first time I used the sudo apt-get command on my Raspberry Pi in China, I had a very bad connectivity with the apt-get mirror automatically selected so I had to find a way to force a direct connection to a specific remote server and this can be easily done by :  

Browsing the list of mirrors from https://www.raspbian.org/RaspbianMirrors  

In my case the closest one was in Japan from the tsukuba server. 

Then you just have to edit the source file at /etc/apt/sources.list  

sudo nano /etc/apt/sources.list  

Add the line and add a # before the other ones.  

_deb http://ftp.tsukuba.wide.ad.jp/Linux/raspbian/raspbian/ jessie main contrib non-free rpi
#deb http://mirrordirector.raspbian.org/raspbian/ jessie main contrib non-free rpi
# Uncomment line below then 'apt-get update' to enable 'apt-get source'
#deb-src http://archive.raspbian.org/raspbian/ jessie main contrib non-free rpi_


TADA!!  

Tell me ig it worked for you.  
