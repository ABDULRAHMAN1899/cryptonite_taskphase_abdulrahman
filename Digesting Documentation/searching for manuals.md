# Searching for Manuals
## Code:
```bash
hacker@man~searching-for-manuals:~$ man man
MAN(1)                                                                                 Manual pager utils                                                                                 MAN(1)

NAME
       man - an interface to the system reference manuals

SYNOPSIS
       man [man options] [[section] page ...] ...
       man -k [apropos options] regexp ...
       man -K [man options] [section] term ...
       man -f [whatis options] page ...
       man -l [man options] file ...
       man -w|-W [man options] page ...

DESCRIPTION
       man  is  the  system's manual pager.  Each page argument given to man is normally the name of a program, utility or function.  The manual page associated with each of these arguments is
       then found and displayed.  A section, if provided, will direct man to look only in that section of the manual.  The default action is to search in all of the available sections  follow‐
       ing a pre-defined order (see DEFAULTS), and to show only the first page found, even if page exists in several sections.

       The table below shows the section numbers of the manual followed by the types of pages they contain.

       1   Executable programs or shell commands
/man -k
Pattern not found
hacker@man~searching-for-manuals:~$ man -k
apropos what?
hacker@man~searching-for-manuals:~$ man -k challenge
ouhapqcoba (1)       - print the flag!
hacker@man~searching-for-manuals:~$ man ouhapqcoba

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

       --ouhapq NUM
              print the flag if NUM is 166

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                                                                                 May 2024                                                                                CHALLENGE(1)
hacker@man~searching-for-manuals:~$ 
hacker@man~searching-for-manuals:~$ man  --ouhapq166
man: unrecognized option '--ouhapq166'
Try 'man --help' or 'man --usage' for more information.
hacker@man~searching-for-manuals:~$ /challenge/challenge  --ouhapq166
Incorrect usage! Please read the challenge man page!
hacker@man~searching-for-manuals:~$ /challenge/challenge --ouhapq 166
Correct usage! Your flag: pwn.college{oY1-U66uhaYUQpqcobatcUSC9I8.dZTM4QDL5kDN0czW}
```
## Learning:
 I learnt how to search manuals in linux
## References:
 did on my own
