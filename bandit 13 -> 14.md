# Bandit level 13 -> 14

## Objective  
To find the SSH private key and use it to log in as bandit14.

## Commands Used  
cp sshkey.private /tmp/bandit13key  
chmod 600 /tmp/bandit13key  
scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private ~/bandit13key  
chmod 600 ~/bandit13key  
ssh -i ~/bandit13key bandit14@bandit.labs.overthewire.org -p 2220

## Explanation  
First, the SSH key file was copied and its permissions were fixed using chmod 600.
Then the key was downloaded to the local machine using scp.
Finally, ssh was used with the private key to log in as bandit14.

## Outcomes  
Learned how to log in using an SSH private key.
