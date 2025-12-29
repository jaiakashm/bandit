# Bandit level 18 -> 19

## Objective  
To read the password for the next level from the readme file.

## Commands Used  
ssh -p 2220 bandit18@bandit.labs.overthewire.org "cat readme"

## Explanation  
Normal SSH login does not give an interactive shell for this level.
So the command was passed directly while connecting using SSH.
This allowed reading the readme file and getting the password.

## Outcomes  
Learned how to work with non-interactive shells using SSH.  
flag: cGWpMaKXVwDUNgPAVJbWYUgHVn9zl3j8
