---
layout: page
title: Command lines I use the most
subtitle: I often need to copy and paste them
published: true
---

## Youtube-dl
sudo pip install --upgrade youtube-dl  
youtube-dl videurl -o "~/Sync/%(title)s.%(ext)s"  

## Network
hostname -I  
Show your local IP address  

## Files
rm *.mp4.*  
Remove all files with mp4 extension  

nano ~/.config/syncthing/config.xml  
Edit the file  

tail -n 100 file.log  
Display the last 100 lines of a log file  

sudo rm -rfv folderName  
Delete a folder and all its content  

## Crontab
crontab -l  
Show the crontab  
crontab -e  
edit crontab list  

ls -a  
Show all files even hidden ones  

find -name "logo.png"  
Find a file named logo.png  


## Others
pwd  
Show where I am located / Current path  

df -h  
Check disk space  

history | grep xxx
To look for a command entered in the past
