# Bandit level 25 -> 26

## Objective  
To find the password by escaping from the more command.

## Commands Used  
ssh -i mathi bandit26@bandit.labs.overthewire.org -p 2220  
:set shell=/bin/bash  
:shell  

## Explanation  
The SSH login opens a file using the more pager.  
more limits interaction, so the terminal window was made small to pause the output.  
When more paused, v was pressed to enter the vi editor.  
Inside vi, the shell was changed to /bin/bash.  
A shell was opened from vi, giving full access.  
From the shell, the password file was read normally.

## Outcomes  
Learned how to escape from more and use vi to get a shell.  
flag: s0773xxkk0MXfdq0fPRVr9L3jJBU0gCZ
