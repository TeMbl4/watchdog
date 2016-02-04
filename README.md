Watchdog for setrix instances this script use "tom" for running.

For correct usage you should add some change to exec script.
1. Add channel names for monitoring to config
format: 
	Job-1
	Job-2
	& etc.
	(empty string)
some help into config-file

2. Create log directory and set path to it. (example: LOG_DIR="./logs")
3. set absolute path to setrix exec bin. (example: command="/home/setrix001/setrix/setrix"
4. set chmod +x ./watchdog.sh

Copyright Setplex inc.
