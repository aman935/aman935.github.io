---
layout: post
title: Crontab the beast
categories: scripts									
---
#An introduction to Cron

Recently, while creating a cas login program in python, I found crontab. And it was one of the most amazing things that i encountered in linux.

So, those who don't know:

>Cron is a utility that helps programmers and developers to schedule commands to be run repeatedly on their machines. Developers use it to set scripts to be run at repeated intervals (Daily, Monthly, Hourly). 

With cron, you can schedule maintenance jobs, download the new episode of your favorite TV series and what not!

#Installation:
It comes automatically in Ubuntu,Fedora and countless linux distros. But, you can also install it from [here](http://www.unixgeeks.org/security/newbie/unix/cron-1.html "Install cron"). 

#Using it:
cron works with crontab files that contains information about the command to be run and the frequency of that command to be executed. 

So, here's how you create a new job:
1. Check if crontab is installed by executing :
`crontab -e`   
If cron is installed. This will create a new crontab file and open it with an code.
2. You can add your command there after specifying the time and date of execution or the frequency of its execution. 
> For more info on how to write a crontab file [write crontab file][https://corenominal.org/2016/05/12/howto-setup-a-crontab-file/ "Writing crontab file"]. 

Hope, you also find crontab extremely useful, like me ;)
