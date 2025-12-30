# Bandit level 22 -> 23

## Objective  
To find the password from a file whose name is generated using a hash.

## Commands Used  
ls /etc/cron.d  
cat /etc/cron.d/cronjob_bandit23  
cat /usr/bin/cronjob_bandit23.sh  
echo "I am user bandit23" | md5sum | cut -d ' ' -f 1  
cat /tmp/8ca319486bfbbc3663ea0fbe81326349

## Explanation  
First, the cron directory was checked to see scheduled jobs.  
The cronjob for bandit23 was opened to see the script it runs.  
The script showed that the filename is created using an MD5 hash.  
The hash was generated for the string "I am user bandit23".  
Finally, the file with that hashed name was read to get the password.

## Outcomes  
Learned how cron jobs use hashes to store data securely.  
flag: 0Zf11iojMVN55jX3CmStKLyqik54Ga
