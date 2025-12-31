# Bandit level 27 -> 28

## Objective  
To find the password for the next level by cloning a Git repository.

## Commands Used  
git clone ssh://bandit27-git@bandit.labs.overthewire.org:2220/home/bandit27-git/repo  
cd repo  
cat README

## Explanation  
This level can be solved on the local machine.  
First, the Git repository was cloned using the provided SSH URL.  
After cloning, the repository directory was opened.  
The README file inside the repository contained the password.

## Outcomes  
Learned how to clone a Git repository over SSH.  
flag: Y3IpLoSBCceuG7m9uQFf8ZNpS4HZRcN
