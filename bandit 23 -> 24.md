# Bandit level 23 -> 24

## Objective  
To write a script that gets the password for bandit24.

## Commands Used  
ls /etc/cron.d  
cat /etc/cron.d/cronjob_bandit24  
cat /usr/bin/cronjob_bandit24.sh  
nano pass.sh  
chmod +x pass.sh  
cp pass.sh /var/spool/bandit24/foo/  
cat /tmp/bandit24_pass

## Explanation  
First, the cron directory was checked to find the cron job for bandit24.  
The cron job file was opened to see which script it runs.  
The script showed where it executes files from.  
A shell script was created to copy the password to a readable location.  
The script was made executable and copied to the cron execution folder.  
After the cron job ran, the password file was read.

## Outcomes  
Learned how cron jobs execute scripts and how to automate tasks.  
flag: gb8KRRCsshuZXl0tUuR6ypOFJZbf3G8
