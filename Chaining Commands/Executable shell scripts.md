# Executable Shell Scripts
## Code:
```bash
hacker@chaining~executable-shell-scripts:~$ touch chall.sh
hacker@chaining~executable-shell-scripts:~$ echo /challenge/solve >> chall.sh
hacker@chaining~executable-shell-scripts:~$ ls -l
total 44
-rw-r--r-- 1 hacker hacker    4 Oct  9 04:28 COLLEGE
drwxr-xr-x 2 hacker hacker 4096 Oct  1 09:43 Desktop
-rw-r--r-- 1 hacker hacker    8 Oct  9 09:17 PWN
-rw-r--r-- 1 root   hacker   58 Oct  3 11:39 a
-rw-r--r-- 1 hacker hacker   17 Oct 17 12:10 chall.sh
drwxr-xr-x 2 hacker hacker 4096 Oct  9 18:50 flag
-rw-r--r-- 1 hacker hacker  829 Oct  9 09:12 instructions
-rw-r--r-- 1 hacker hacker    0 Oct  9 09:12 my
-rw-r--r-- 1 hacker hacker   93 Oct  9 09:12 myflag
lrwxrwxrwx 1 hacker hacker    5 Oct  6 15:28 not-the-flag -> /flag
-rw-r--r-- 1 root   hacker   77 Oct  9 16:13 out
-rw-r--r-- 1 hacker hacker  435 Oct  9 09:05 the-flag
-rw-r--r-- 1 hacker hacker   68 Oct 17 12:07 x.sh
hacker@chaining~executable-shell-scripts:~$ chmod chall.sh x
chmod: invalid mode: ‘chall.sh’
Try 'chmod --help' for more information.
hacker@chaining~executable-shell-scripts:~$ chmod a+x chall.sh
hacker@chaining~executable-shell-scripts:~$ ./chall.sh
Congratulations on your shell script execution! Your flag:
pwn.college{QeryRALVmAJ-oWvzvG-8WbjJiS2.dRzNyUDL5kDN0czW}
```
## Learning:
 I learnt how to execute shell scripts without bash in linux
## References:
 did on my own
