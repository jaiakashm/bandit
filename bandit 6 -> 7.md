# Bandit level 6 -> 7

## Objective  
To find the password stored somewhere on the server.

## Commands Used  
cd /  
find . -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null  
cat /var/lib/dpkg/info/bandit7.password

## Explanation  
First, cd / was used to move to the root directory.
The find command was used to search for a file owned by user bandit7, group bandit6, and size 33 bytes.
Error messages were hidden using 2>/dev/null.
After finding the file path, cat was used to read the password.

## Outcomes  
Learned how to filter files based on user, group, and size.  
flag: morbNTDkSW6jIluCym0dMaLn0IFVAAj
