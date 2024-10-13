# Killing Processes
## Code:
```bash
hacker@processes~killing-processes:~$ ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.0   1056   640 ?        Ss   11:00   0:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /run/dojo/bin/sleep 6h
root           7  0.0  0.0   5052  2560 ?        S    11:00   0:00 /run/dojo/bin/sleep 6h
root          70  0.0  0.0   4732  2880 ?        S    11:00   0:00 su -c /challenge/.launcher hacker
hacker        72  0.0  0.0   4976  3520 ?        Ss   11:00   0:00 /challenge/dont_run
hacker        73  0.0  0.0   5052  2240 ?        S    11:00   0:00 sleep 6h
hacker        82  0.6  0.0 1100320 63640 ?       Sl   11:00   0:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexe
hacker       103  4.7  0.0 1316092 87836 ?       Sl   11:00   0:06 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexe
hacker       144  4.3  0.0 1335576 99756 ?       Sl   11:00   0:05 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node --dns-result-order=ipv4first /nix/store/3v4hdb2gmpj7jv2z848ika
hacker       169  0.7  0.0 1104412 54616 ?       Rl   11:01   0:01 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexe
hacker       181  0.0  0.0   5368  4160 pts/0    Ss   11:01   0:00 /run/dojo/bin/bash --init-file /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/out/vs/workb
hacker       873  0.0  0.0   7868  3200 pts/0    R+   11:03   0:00 ps aux
hacker@processes~killing-processes:~$ kill 72
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{MNSKZZCKfc0VFrn9CunHL5Dxlil.dJDN4QDL5kDN0czW}
```
## Learning:
 I learnt how to kill processes in linux
## References:
 did on my own
