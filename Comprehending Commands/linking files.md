# Linking files
## Code:
```bash
hacker@commands~linking-files:~$ ln -s /home/hacker/not-the-flag /flag
ln: failed to create symbolic link '/flag': File exists
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
ln: failed to create symbolic link '/home/hacker/not-the-flag': File exists
hacker@commands~linking-files:~$ file~/not-the-flag
bash: file~/not-the-flag: No such file or directory
hacker@commands~linking-files:~$ file ~/not-the-flag 
/home/hacker/not-the-flag: symbolic link to /flag
hacker@commands~linking-files:~$ cat ~/not-the-flag
cat: /home/hacker/not-the-flag: Permission denied
hacker@commands~linking-files:~$ cat /challenge/flag
cat: /challenge/flag: No such file or directory
hacker@commands~linking-files:~$ cat/challenge/catflaf
bash: cat/challenge/catflaf: No such file or directory
hacker@commands~linking-files:~$ cat/challenge/catflag
bash: cat/challenge/catflag: No such file or directory
hacker@commands~linking-files:~$ 
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{MK-z94QKOe8BWoi3ryA5oujfr5O.dlTM1UDL5kDN0czW}
```
## Learning:
 I learnt how to use ln -s in linux
## References:
 did on my own
