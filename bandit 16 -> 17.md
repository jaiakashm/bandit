# Bandit level 16 -> 17

## Objective  
To find the RSA key from an open port on the server using OpenSSL.

## Commands Used  
nmap -p 31000-32000 localhost  
openssl s_client -quiet -connect localhost:<port>  
chmod 600 key  
scp -P 2220 bandit16@bandit.labs.overthewire.org:/tmp/key .  
ssh -i key bandit17@bandit.labs.overthewire.org -p 2220

## Explanation  
First, nmap was used to scan open ports.
Then OpenSSL was used to test which port accepts an SSL connection.
The correct port returned an RSA private key.
The key was saved, permissions were fixed, and SSH was used to log in as bandit17.

## Outcomes  
Learned how to find an RSA private key from an open SSL port and use it to log in via SSH.
