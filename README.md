# raspberrypifancontrol
Download the python script
To Set up in cron, copy the script to /home/pi/bin (assumes 'pi' is user name).  
Add this entry to crontab (adjust pin and temp as needed): */1 * * * * /home/pi/bin/fantemp.py --p 14 -t 
