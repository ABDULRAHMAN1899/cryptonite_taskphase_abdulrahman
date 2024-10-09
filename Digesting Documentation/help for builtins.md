# Help for builtins
## Code:
```bash
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!
    
    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "4yNMEg9E".
hacker@man~help-for-builtins:~$ challenge --secret 4yNMEg9E
Correct! Here is your flag!
pwn.college{4yNMEg9E0KUcFotvJ5oHSRPVgMc.dRTM5QDL5kDN0czW}
```
## Learning:
 I learnt how to use help for builtins in linux
## References:
 did on my own
