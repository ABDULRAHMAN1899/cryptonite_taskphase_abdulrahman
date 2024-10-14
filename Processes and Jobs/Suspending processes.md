# Suspending processe
## Code:
```bash
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in 
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         239     172  0 11:46 pts/0    00:00:00 bash /challenge/run
root         241     239  0 11:46 pts/0    00:00:00 ps -f

I don't see a second me!

To pass this level, you need to suspend me and launch me again! You can 
background me with Ctrl-Z or, if you're not ready to do that for whatever 
reason, just hit Enter and I'll exit!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in 
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root         239     172  0 11:46 pts/0    00:00:00 bash /challenge/run
root         383     172  0 11:47 pts/0    00:00:00 bash /challenge/run
root         386     383  0 11:47 pts/0    00:00:00 ps -f

Yay, I found another version of me! Here is the flag:
pwn.college{gMCRcKNmnSgicxemi_CtB-SswLn.dVDN4QDL5kDN0czW}
```
## Learning:
 I learnt how to suspend processes in linux
## References:
 did on my own
