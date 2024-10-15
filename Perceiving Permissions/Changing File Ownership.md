## Code:
```bash
hacker@permissions~changing-file-ownership:~$ ls -l
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
hacker@permissions~changing-file-ownership:~$ chown hacker /flag
hacker@permissions~changing-file-ownership:~$ cat flag
cat: flag: Is a directory
hacker@permissions~changing-file-ownership:~$ /flag
bash: /flag: Permission denied
hacker@permissions~changing-file-ownership:~$ cat /flag
pwn.college{cKlP4tONDRdODAEcMxLlfzx5-Vt.dFTM2QDL5kDN0czW}
```
## Learning:
 I learnt how to Change file owner in linux
## References:
 did on my own
