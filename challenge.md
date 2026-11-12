# Challenge: Security Detective

## Question 1
Answer: I am shanzaanum7-hub. My home folder is /home/shanzaanum7-hub.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu. It runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has 5.2Gi of total RAM. The free disk space is 4.2G available (9.8G total, 55% used).
Commands: free -h, df -h /

## Question 4
Answer: Two users can log in with /bin/bash: root and shanzaanum7-hub.
Commands: grep bash /etc/passwd

## Question 5
Answer: 239 lines were counted in ps aux. This includes the header line, so about 238 processes are running.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created at 17:48:11 and deleted at 17:52:41 on 2026-11-12 (time zone +00:00).
Commands: sudo grep lab5user /var/log/auth.log
