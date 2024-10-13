# Listing processes
## Code:
```bash
hacker@processes~listing-processes:~$ ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.1  0.0   1056   640 ?        Ss   10:50   0:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /run/dojo/bin/sleep 6h
root           7  0.0  0.0   5052  2240 ?        S    10:50   0:00 /run/dojo/bin/sleep 6h
root          68  0.0  0.0   4132  2560 ?        S    10:50   0:00 /challenge/9379-run-547
root          72  0.0  0.0   2744  1600 ?        S    10:50   0:00 sleep 6h
hacker        81  3.1  0.0 1100064 62120 ?       Sl   10:50   0:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexe
hacker       102 24.9  0.0 1355692 130728 ?      Sl   10:50   0:06 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexe
hacker       143 12.9  0.0 1331348 90700 ?       Sl   10:50   0:02 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node --dns-result-order=ipv4first /nix/store/3v4hdb2gmpj7jv2z848ika
hacker       168  2.8  0.0 1038108 55536 ?       Rl   10:51   0:00 /nix/store/bmmjbvb8hishfrg78ygjlynpq3ikpl39-nodejs-20.15.1/bin/node /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexe
hacker       180  0.0  0.0   5368  4160 pts/0    Ss   10:51   0:00 /run/dojo/bin/bash --init-file /nix/store/3v4hdb2gmpj7jv2z848ikakhzl9rjgwh-code-server/libexec/code-server/lib/vscode/out/vs/workb
hacker       307  0.0  0.0   7868  3520 pts/0    R+   10:51   0:00 ps aux
hacker@processes~listing-processes:~$ /challenge/9379-run-547
Yahaha, you found me! Here is your flag:
pwn.college{cDbH6IBv8-Wo-WgkhBOXMVg1lRi.dhzM4QDL5kDN0czW}
Now I will sleep for a while (so that you could find me with 'ps').
```
## Learning:
 I learnt how to list processes in linux
## References:
 did on my own
