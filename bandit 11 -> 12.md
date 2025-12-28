# Bandit level 11 -> 12

## Objective  
To find the password by applying ROT13 decoding.

## Commands Used  
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

## Explanation  
The file was read using cat.
The output was passed to tr to apply ROT13 conversion.
This revealed the correct password.

## Outcomes  
Learned how to decode ROT13 using the tr command.  
flag: 7x16WNeHl5YklhWsfFqoognUTyj9Q4
