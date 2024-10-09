# Matching paths with []
## Code:
```bash
hacker@globbing~matching-paths-with-:~$ /challenge/run /file_[bash]
Error: you will need to specify the path to the files as part of your glob 
argument, since they are in a different directory than your current working 
directory!
hacker@globbing~matching-paths-with-:~$ cd /home/hacker
hacker@globbing~matching-paths-with-:~$ /challenge/run /home/hacker/file_[bash]
Error: you will need to specify the path to the files as part of your glob 
argument, since they are in a different directory than your current working 
directory!
hacker@globbing~matching-paths-with-:~$ /challenge/run /challenge/file_[bash]
Error: you will need to specify the path to the files as part of your glob 
argument, since they are in a different directory than your current working 
directory!
HINT: You are trying to specify files in the /challenge directory, but the 
files are actually in the /challenge/files directory.
hacker@globbing~matching-paths-with-:~$ /challenge/run /challenge/files/file_[bash]
You got it! Here is your flag!
pwn.college{ASTeSG-16qlAOf7yXeUMhs0N3h1.dRjM4QDL5kDN0czW}
```
## Learning:
 I learnt how to use [] commands in linux
## References:
 did on my own
