# Bandit level 29 -> 30

## Objective  
To find the password stored in a Git repository branch.

## Commands Used  
git clone ssh://bandit29-git@bandit.labs.overthewire.org:2220/home/bandit29-git/repo  
cd repo  
git branch -r  
git checkout dev  
git show README.md

## Explanation  
First, the Git repository was cloned using the SSH link.  
The default branch did not contain the password.  
All remote branches were listed using git branch -r.  
The dev branch was checked out.  
The password was found inside the README file in the dev branch.

## Outcomes  
Learned how to work with branches in Git and find hidden data.  
flag: qp30ex3vLZ5MDG1n91YowTv4Q8I7CDZL
