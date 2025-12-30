# Bandit level 20 -> 21

## Objective  
To get the password by creating a connection using netcat.

## Commands Used  
nc -l 5555  
./suconnect 5555

## Explanation  
First, file permissions were checked and the file was found to have setuid enabled.  
In one terminal, netcat was started on port 5555.  
In another terminal, the suconnect file was run with the same port.  
After entering the current password, the password for the next level was received.

## Outcomes  
Learned how to use netcat with setuid programs.  
flag: EeoULMCra2qd0SKy561DX7s1CpBuOBt
