# Redirecting Input
## Code:
```bash
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ PWN < /challenge/run
bash: PWN: command not found
hacker@piping~redirecting-input:~$ echo PWN < /challenge/run
PWN
hacker@piping~redirecting-input:~$ /challenge/run
You have not redirected anything to my standard input. Please do so, using '<'.
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read 
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{Ufdu4oJPQWlz431Gh-QQPrGKiXl.dBzN1QDL5kDN0czW}
```
## Learning:
 I learnt how to Redirect Input in linux
## References:
 did on my own
