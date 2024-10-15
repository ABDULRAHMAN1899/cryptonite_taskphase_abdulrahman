# Fun with group names
## Code:
```bash
hacker@permissions~fun-with-groups-names:~$ id
uid=1000(hacker) gid=1000(grp8298) groups=1000(grp8298)
hacker@permissions~fun-with-groups-names:~$ ls -l
total 36
-rw-r--r-- 1 hacker grp8298    4 Oct  9 04:28 COLLEGE
drwxr-xr-x 2 hacker grp8298 4096 Oct  1 09:43 Desktop
-rw-r--r-- 1 hacker grp8298    8 Oct  9 09:17 PWN
-rw-r--r-- 1 root   grp8298   58 Oct  3 11:39 a
drwxr-xr-x 2 hacker grp8298 4096 Oct  9 18:50 flag
-rw-r--r-- 1 hacker grp8298  829 Oct  9 09:12 instructions
-rw-r--r-- 1 hacker grp8298    0 Oct  9 09:12 my
-rw-r--r-- 1 hacker grp8298   93 Oct  9 09:12 myflag
lrwxrwxrwx 1 hacker grp8298    5 Oct  6 15:28 not-the-flag -> /flag
-rw-r--r-- 1 root   grp8298   77 Oct  9 16:13 out
-rw-r--r-- 1 hacker grp8298  435 Oct  9 09:05 the-flag
hacker@permissions~fun-with-groups-names:~$ chgrp grp8298 /flag
hacker@permissions~fun-with-groups-names:~$ cat /flag
pwn.college{0iSqS_zmKDsFVHfZONxwHUWBs_V.dJzNyUDL5kDN0czW}
```
## Learning:
 I learnt how to use cat in linux
## References:
 did on my own
