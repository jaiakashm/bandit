# Bandit level 12 -> 13

## Objective  
To find the password in data.txt which is a hexdump file compressed multiple times.

## Commands Used  
tar  
gzip  
bzip2  
xxd  
mkdir  
cp  
mv  
file  

## Explanation  
The data.txt file was copied to a temporary directory.
The hexdump was reversed using xxd.
The file command was used to identify the file type.
Based on the type, gzip, bzip2, or tar was used to extract the file.
This process was repeated until a readable text file was found.

## Outcomes  
Learned how to handle hexdump files and multiple compression formats.  
flag: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
