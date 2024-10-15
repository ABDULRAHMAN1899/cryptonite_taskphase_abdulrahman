# The Suid bit
## Code:
```bash
hacker@permissions~the-suid-bit:~$ chmod u+s /challenge/getroot
hacker@permissions~the-suid-bit:~$ cat /flag
cat: /flag: Permission denied
hacker@permissions~the-suid-bit:~$ ls -l /challenge/getroot
-rwsr-xr-x 1 root root 155 Jul 12 10:30 /challenge/getroot
hacker@permissions~the-suid-bit:~$ u+r /challenge/getroot
bash: u+r: command not found
hacker@permissions~the-suid-bit:~$ chmod u+r /challenge/getroot
hacker@permissions~the-suid-bit:~$ cat /flag
cat: /flag: Permission denied
hacker@permissions~the-suid-bit:~$ /challenge/getroot
SUCCESS! You have set the suid bit on this program, and it is running as root! 
Here is your shell...
root@permissions~the-suid-bit:~# cat /flag
pwn.college{QMXSdWGeTVJpHkpSTER_de9dt9V.dNTM2QDL5kDN0czW}
```
## Learning:
 I learnt how to use suid bit in linux
## References:
 did on my own
