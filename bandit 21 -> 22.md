# Bandit level 21 -> 22

## Objective  
To get the password using cron jobs.

## Commands Used  
ls /etc/cron.d  
cat /etc/cron.d/cronjob_bandit22  
cat /usr/bin/cronjob_bandit22.sh  
cat /tmp/t7061ds9S0RqQh9aMcz6ShpAoZKF7fgv

## Explanation  
First, the cron directory was checked to see scheduled tasks.  
The cronjob for bandit22 was opened to see which script runs.  
The script file showed where the password was saved.  
Finally, the output file was read to get the password.

## Outcomes  
Learned how cron jobs work and where they store output.  
flag: RaeOUfB9v0UzbCdn9cY0qQnds9Gr58Q
