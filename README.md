# linux_cool_commands

https://telehack.com/

rev file.txt

factor 100

# yum install cowsay
cowsay we are LW

# yes i m Lw

espeak-ng "i love you"

# chpasswd
user1:pass1
user2:pass2
user3:pass3

ctrl +d

# gnome-screenshot -f file.png

# eof file.png

# man -k <insert keyword>   # use / and search for a term by typing it

# hide ur work
ctrl + s
unhide
ctrl + q


Alt+Backspace: Deletes the previous word.
Alt+F: Skips ahead to the next space.
Alt+B: Skips back to the previous space.
Ctrl+U: Cuts all text up to the cursor.
Ctrl+K: Cuts all text after the cursor until end of line.
Ctrl+A: Moves the cursor to the start of line.
Ctrl+E: Moves the cursor to the end of line.
CTRL, and U 	It can remove the complete command (line).

# shutdown 14:00 

# script
# script -T mytime.log
# scriptlive -T mytime.log


Use !{command} for executing the previous instance of command quickly
Use !! for Executing the Last Command
 Use “CTRL+R” for Repeating the Last Matching Command

# nohup firefox

# echo file01 file02 | xargs touch

# mtr www.google.com

“nl command” to list them in a numbered fashion.
# nl /etc/passwd

# ls | shuf (shuffle Input)

#  “last” command show the history of last logged in users. T

how do you obtain your External IP address
# curl ifconfig.me

# yum install figlet
# watch -t -n1 "date +%T|figlet"

# yum install dstat
# dstat

# ‘bind -p‘ command will show all the shortcuts available for BASH shell.

# user accounting command, ac
$ ac -d
$ ac -p

# type dir rather than ls because you've worked with the Microsoft Windows command line and can't break the habit
ls -la /usr/bin/dir
ls -la /usr/bin/ls

$ zipcloak zipfile.zip 
$ unzip zipfile.zip 

#  authconfig --enablefaillock --faillockargs="deny=3 unlock_time=600" --update
~]# grep -i faillock /etc/sysconfig/authconfig
FAILLOCKARGS="deny=3 unlock_time=600"
USEFAILLOCK=yes

 ~]# authselect enable-feature with-faillock
~]# grep -vE '^#|^$' /etc/security/faillock.conf
silent
deny = 3
unlock_time = 600
~]# authselect disable-feature with-faillock

~]# faillock  --reset --user user1

# Linux locking Password
passwd -l {username}
passwd -u {username}











sudo !!
alias gerp=grep

## get top process eating memory
ps auxf | sort -nr -k 4 | head -10

# pip3 install thefuck --user
# fuck
https://github.com/nvbn/thefuck?ref=hackernoon.com

# vim +X filename

# Find if there are files containing specific text
grep -Pri Search_Term path_to_directory

find /home/user -type f sensetive_data.txt
find. -type f -size 100M

find /home/user/sensetive_files/ -type f -exec chmod 644 {}

# use the previous argument:
cd !$

# you want to perform a specific task but don’t know the correct command.
# apropos "copy files" 





