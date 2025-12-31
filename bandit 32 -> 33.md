# Bandit level 32 -> 33

## Objective  
To find the password by escaping from the uppercase shell.

## Commands Used  
$0  
cat /etc/bandit_pass/bandit33

## Explanation  
When we log in to this level, we are placed in a shell that only accepts uppercase commands.  
To escape this restricted shell, we use the $0 command, which starts a normal shell.  
After getting the normal shell, we can run the cat command to read the password file.

## Outcomes  
Learned how to escape from a restricted shell environment.  
flag: qTdbs5D5i2VJwkO8mEyEyTL8izoeJ0
