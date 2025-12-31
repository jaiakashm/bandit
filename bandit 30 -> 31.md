# Bandit level 30 -> 31

## Objective  
To retrieve the password from a Git repository using tags.

## Commands Used  
git clone ssh://bandit30-git@bandit.labs.overthewire.org:2220/home/bandit30-git/repo  
cd repo  
git tag  
git show secret

## Explanation  
First, the Git repository was cloned using the SSH link.  
After entering the repository, Git tags were listed using git tag.  
One tag pointed to a hidden object named secret.  
The command git show secret was used to display its contents.  
The password was found inside this tag.

## Outcomes  
Learned how Git tags can store hidden information.  
flag: fb5S2xb7bRyFmAvQYQGEqsbvYJqhnDy
