# Bandit level 28 -> 29

## Objective  
To find the password from a Git repository by checking commit history.

## Commands Used  
git clone ssh://bandit28-git@bandit.labs.overthewire.org:2220/home/bandit28-git/repo  
cd repo  
git log  
git show <commit-id>

## Explanation  
This level is similar to the previous one and can be done on the local machine.  
First, the Git repository was cloned using the SSH link.  
Then, git log was used to view the commit history.  
The latest commit ID was copied and checked using git show.  
The password was found inside the commit content.

## Outcomes  
Learned how sensitive data can be found using Git commit history.  
flag: 4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7
