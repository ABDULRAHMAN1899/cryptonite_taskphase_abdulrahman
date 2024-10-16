# Cracking Passwords
## Code:
```bash
hacker@users~cracking-passwords:~$ cd /challenge
hacker@users~cracking-passwords:/challenge$ john ./shadow-leak
Loaded 1 password hash (crypt, generic crypt(3) [?/64])
Press 'q' or Ctrl-C to abort, almost any other key for status
aardvark         (zardus)
1g 0:00:00:20 100% 2/3 0.04892g/s 284.8p/s 284.8c/s 284.8C/s Johnson..buzz
Use the "--show" option to display all of the cracked passwords reliably
Session completed
hacker@users~cracking-passwords:/challenge$ --s
bash: --s: command not found
hacker@users~cracking-passwords:/challenge$ --show
bash: --show: command not found
hacker@users~cracking-passwords:/challenge$ su zardus
Password: 
zardus@users~cracking-passwords:/challenge$ /challenge/run
Congratulations, you have become Zardus! Here is your flag:
pwn.college{sCtlsjGy6Jy5mZWR2RueJn6bUOD.ddTN0UDL5kDN0czW}
```
## Learning:
 I learnt how to crack passwords in linux
## References:
 did on my own
