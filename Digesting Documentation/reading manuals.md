# Reading manuals
## Code:
```bash
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                                                                           Challenge Commands                                                                           CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --kmoszm NUM
              print the flag if NUM is 045

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                                                                                 May 2024                                                                                CHALLENGE(1)
hacker@man~reading-manuals:~$ cat --fortune
cat: unrecognized option '--fortune'
Try 'cat --help' for more information.
hacker@man~reading-manuals:~$ cat --help
Usage: cat [OPTION]... [FILE]...
Concatenate FILE(s) to standard output.

With no FILE, or when FILE is -, read standard input.

  -A, --show-all           equivalent to -vET
  -b, --number-nonblank    number nonempty output lines, overrides -n
  -e                       equivalent to -vE
  -E, --show-ends          display $ at end of each line
  -n, --number             number all output lines
  -s, --squeeze-blank      suppress repeated empty output lines
  -t                       equivalent to -vT
  -T, --show-tabs          display TAB characters as ^I
  -u                       (ignored)
  -v, --show-nonprinting   use ^ and M- notation, except for LFD and TAB
      --help        display this help and exit
      --version     output version information and exit

Examples:
  cat f - g  Output f's contents, then standard input, then g's contents.
  cat        Copy standard input to standard output.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/cat>
or available locally via: info '(coreutils) cat invocation'
hacker@man~reading-manuals:~$ cat --version
cat (GNU coreutils) 9.5
Packaged by https://nixos.org
Copyright (C) 2024 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Written by Torbjörn Granlund and Richard M. Stallman.
hacker@man~reading-manuals:~$ cat OPTION
cat: OPTION: No such file or directory
hacker@man~reading-manuals:~$ /challenge/challenge
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:~$ /challenge/challenge --kmoszm 045
Correct usage! Your flag: pwn.college{kmSTosDzmFVzpOr0GqlAaTSNiSM.dRTM4QDL5kDN0czW}
```
## Learning:
 I learnt how to read manuals in linux
## References:
 did on my own
