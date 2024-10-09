# Helpful programs
## Code:
```bash
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 714
hacker@man~helpful-programs:~$ /challenge/challenge -g 714
Correct usage! Your flag: pwn.college{YL7TD1JJSOhTOFbczaozZLWeFvV.ddjM4QDL5kDN0czW}

HELP FOR BUILTINS

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
 I learnt how to use help in linux
## References:
 did on my own
