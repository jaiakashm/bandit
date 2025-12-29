# Bandit level 19 -> 20

## Objective  
To find the password by running a file as bandit20.

## Commands Used  
ls -l  
./bandit20-do cat /etc/bandit_pass/bandit20

## Explanation  
The ls -l command was used to check file permissions.
The file has the setuid bit set, so it runs as bandit20.
Running the file allowed reading the password for the next level.

## Outcomes  
Learned about the setuid concept in Linux.  
flag: qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
