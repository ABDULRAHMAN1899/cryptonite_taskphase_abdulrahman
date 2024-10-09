# Touching files
## Code:
```bash
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ ls
bin  hsperfdata_root  tmp.G9qthVCks5  vscode-git-133fcbb959.sock  vscode-ipc-29fe02bd-2da7-48cf-a098-5950c4cf5dff.sock  vscode-ipc-b5c9da65-10fa-4618-b0db-2fede83ace74.sock
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ ls
bin  hsperfdata_root  pwn  tmp.G9qthVCks5  vscode-git-133fcbb959.sock  vscode-ipc-29fe02bd-2da7-48cf-a098-5950c4cf5dff.sock  vscode-ipc-b5c9da65-10fa-4618-b0db-2fede83ace74.sock
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.G9qthVCks5  vscode-git-133fcbb959.sock  vscode-ipc-29fe02bd-2da7-48cf-a098-5950c4cf5dff.sock  vscode-ipc-b5c9da65-10fa-4618-b0db-2fede83ace74.sock
hacker@commands~touching-files:/tmp$ cd
hacker@commands~touching-files:~$ /challenge/run
Success! Here is your flag:
pwn.college{wnBCX2uHKp7e_vjfQlCOUuEi5SW.dBzM4QDL5kDN0czW}
```
## Learning:
 I learnt how to use touch in linux
## References:
 did on my own
