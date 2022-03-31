# LinuxCommands
Summary the linux commands
pwd 
Print working directory, i.e., display the name of my current directory on the  screen.

hostname 
Print the name of the local host (the machine on which you are working). Use netconf (as root) to change the name of the machine.

id username
Print user id (uid) and his/her group id (gid), effective id (if different than the real id) and the supplementary groups.

date 
Print or change the operating system date and time. E.g., I could change the date and time to 2000-12-31 23:57 using this command: date 123123572000 To set the 
hardware (BIOS) clock from the system (Linux) clock, use the command (as root) setclock

who 
Determine the users logged on the machine.

finger  user_name 
System info about a user. Try: finger root . displays the user's login name, real name, terminal name and write status (as a ``*'' after the terminal name if write permission is denied), idle time, login time, office location .

history | more 
Show the last (1000 or so) commands executed from the command line on the current account. The "| more" causes the display to stop after each screenful.


