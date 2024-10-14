# Process Exit codes
## Code:
```bash
hacker@processes~process-exit-codes:~$ /challenge/get-code
Exiting with an error code!
hacker@processes~process-exit-codes:~$ echo $?
32
hacker@processes~process-exit-codes:~$ challenge/submit-code
bash: challenge/submit-code: No such file or directory
hacker@processes~process-exit-codes:~$ /challenge/submit-code
You must run /challenge/submit-code with the exit code you retrieved from 
/challenge/get-code as the first argument:

Usage: /challenge/submit-code [EXIT_CODE]
hacker@processes~process-exit-codes:~$ /challenge/submit-code 32
CORRECT! Here is your flag:
pwn.college{cy-i3cu2JL4kgdy9NoWTtW-FvBD.dljN4UDL5kDN0czW}
```
## Learning:
 I learnt how to Process Exit codes in linux
## References:
 did on my own
