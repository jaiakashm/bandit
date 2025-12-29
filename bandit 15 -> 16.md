# Bandit level 15 -> 16

## Objective  
To make an OpenSSL connection and get the password for the next level.

## Commands Used  
openssl s_client -connect localhost:30001

## Explanation  
The openssl command was used to create a secure connection to localhost on port 30001.
After the connection was made, the current level password was entered.
The server then returned the password for the next level.

## Outcomes  
Learned how to make a secure connection using OpenSSL.  
flag: kSkvUpMQ7lBYCM4GBPvCvT1BfwRy0Dx
