# Changing Permissions
## Code:
```bash
hacker@permissions~changing-permissions:~$ ls -l
total 36
-rw-r--r-- 1 hacker hacker    4 Oct  9 04:28 COLLEGE
drwxr-xr-x 2 hacker hacker 4096 Oct  1 09:43 Desktop
-rw-r--r-- 1 hacker hacker    8 Oct  9 09:17 PWN
-rw-r--r-- 1 root   hacker   58 Oct  3 11:39 a
drwxr-xr-x 2 hacker hacker 4096 Oct  9 18:50 flag
-rw-r--r-- 1 hacker hacker  829 Oct  9 09:12 instructions
-rw-r--r-- 1 hacker hacker    0 Oct  9 09:12 my
-rw-r--r-- 1 hacker hacker   93 Oct  9 09:12 myflag
lrwxrwxrwx 1 hacker hacker    5 Oct  6 15:28 not-the-flag -> /flag
-rw-r--r-- 1 root   hacker   77 Oct  9 16:13 out
-rw-r--r-- 1 hacker hacker  435 Oct  9 09:05 the-flag
hacker@permissions~changing-permissions:~$ ls -l /flag
-r-------- 1 root root 58 Oct 15 11:48 /flag
hacker@permissions~changing-permissions:~$ chmod u+r /flag
hacker@permissions~changing-permissions:~$ cat /flag
cat: /flag: Permission denied
hacker@permissions~changing-permissions:~$ chmod o+r /flag
hacker@permissions~changing-permissions:~$ cat /flag
pwn.college{gkR1k4vPkqIqxJ7wscj8ae50b1c.dNzNyUDL5kDN0czW}
```
## Learning:
 I learnt how to change permissions in linux
## References:
 did on my own
