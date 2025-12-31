# OverTheWire Bandit – Writeups

This repository contains my personal notes and solutions for the *OverTheWire Bandit* wargame.  
Bandit is designed to teach basic Linux commands, shell usage, and security concepts.

## About Bandit

Bandit is a beginner-friendly wargame provided by OverTheWire.  
Each level introduces a new Linux or security concept such as:
- File permissions
- SSH
- Encoding and decoding
- Networking
- Cron jobs
- Git basics
- Setuid binaries
- Restricted shells

## Repository Structure

Each file in the Bandit/ folder explains *one level transition*.

### Example:

Bandit/ ├── bandit 0 -> 1.md ├── bandit 1 -> 2.md ├── bandit 2 -> 3.md ├── ... ├── bandit 32 -> 33.md

### Each level file includes:
- *Objective* – What the level asks us to do  
- *Commands Used* – Commands executed to solve the level  
- *Explanation* – Simple explanation of the solution  
- *Outcome* – What I learned (and the password)

## Tools & Commands Used

Some commonly used commands in these levels:
- ls, cat, cd
- grep, strings, base64, tr
- ssh, scp, nc, openssl
- chmod, setuid
- cron
- git clone, git log, git show
- Shell escaping techniques

## What I Learned

By completing Bandit, I learned:
- How Linux permissions work
- How to find hidden data in files
- How encoding and encryption work
- How network services behave
- How cron jobs can leak data
- How Git history can expose secrets
- How restricted shells can be escaped
