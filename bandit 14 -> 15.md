# Bandit level 14 -> 15

## Objective  
To get the password for the next level using netcat.

## Commands Used  
cat /etc/bandit_pass/bandit14 | nc localhost 30000

## Explanation  
First, the current level password was read from the file.
Then netcat was used to connect to localhost on port 30000.
The password was sent through the connection and the next level password was received.

## Outcomes  
Learned how to use netcat to connect to a service and send data.  
flag: 8xCjmgoKbgLHHAZIGe5Tmu4M2tKJQo
