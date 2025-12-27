# Bandit level 9 -> 10

## Objective  
To find the password in data.txt where it is preceded by ======.

## Commands Used  
strings data.txt | grep "====="

## Explanation  
The strings command was used to extract readable text from data.txt.
Then grep was used to find the line that starts with ======.
The password was found in that output.

## Outcomes  
Learned how to extract human-readable strings from a file.  
flag: FGUW5ilLVrX9kMYMmiN4MgbpfMiqey
