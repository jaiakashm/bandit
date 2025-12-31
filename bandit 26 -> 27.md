# Bandit level 26 -> 27

## Objective  
To find the password using a file with setuid permission.

## Commands Used  
ls  
./bandit27-do cat /etc/bandit_pass/bandit27

## Explanation  
First, the files in the directory were listed using ls.  
A file named bandit27-do was found with setuid permission.  
This file runs commands as the bandit27 user.  
The file was executed to read the password file of bandit27.

## Outcomes  
Learned how setuid binaries can be used to run commands as another user.  
flag: upsNCc7vzaRDx6oZC6GiR6Erwe1MowGB
