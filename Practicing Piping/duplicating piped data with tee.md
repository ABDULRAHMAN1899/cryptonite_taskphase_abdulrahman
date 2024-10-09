# Create Duplicating piped data with tee
## Code:
```bash
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code 
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the 
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee out | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code 
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the 
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat out
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "8SCMcRcU"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret 8SCMcRcU | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{8SCMcRcUn0tMPgJUL_aflXBPg_5.dFjM5QDL5kDN0czW}
```
## Learning:
 I learnt how to use tee in linux
## References:
 did on my own
