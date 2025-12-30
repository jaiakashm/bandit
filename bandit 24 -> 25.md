# Bandit level 24 -> 25

## Objective  
To find the password by brute forcing a 4-digit PIN.

## Commands Used  
cd /tmp  
for i in {0000..9999}; do printf "%s %04d\n" "$(cat /etc/bandit_pass/bandit24)" "$i"; done | nc localhost 30002

## Explanation  
First, we moved to the /tmp directory.  
A loop was used to generate all 4-digit PINs from 0000 to 9999.  
Each PIN was sent along with the bandit24 password.  
The output was piped to the service running on port 30002 using netcat.  
When the correct PIN was sent, the server returned the password.

## Outcomes  
Learned how brute-force attacks work using loops and netcat.  
flag: iC68ttT4KSNe1armKiwbQNmB3YJP3q4
