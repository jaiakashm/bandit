# Bandit level 5 -> 6

## Objective  
To find the password in a file that is not executable, human-readable, and 1033 bytes in size.

## Commands Used  
find inhere -type f -size 1033c ! -executable

## Explanation  
The find command was used inside the inhere directory.
Filters were applied to get only files that are regular files, exactly 1033 bytes in size, and not executable.
This helped to locate the correct file and read the password.

## Outcomes  
Learned how to filter files using the find command instead of brute forcing.  
flag: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
