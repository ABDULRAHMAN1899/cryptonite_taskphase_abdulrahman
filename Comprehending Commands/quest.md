# An epic filesystem quest
## Code:
```bash
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
SNIPPET  bin  boot  challenge  dev  etc  flag  home  lib  lib32  lib64  libx32  media  mnt  nix  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
hacker@commands~an-epic-filesystem-quest:/$ cat SNIPPET
Great sleuthing!
The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Size5/Regular

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/$ cat Regular
cat: Regular: No such file or directory
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Size5/Regular
cat: /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Size5/Regular: Is a directory
hacker@commands~an-epic-filesystem-quest:/$ ls /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Size5/Regular
INFO-TRAPPED  Main.js
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Gyre-Pagella/Size5/Regular/INFO-TRAPPED
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/include/config/acpi/rev
hacker@commands~an-epic-filesystem-quest:/$ ls /opt/linux/linux-5.4/include/config/acpi/rev
REVELATION  override
hacker@commands~an-epic-filesystem-quest:/$ cat /opt/linux/linux-5.4/include/config/acpi/rev/REVELATION
Yahaha, you found me!
The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ ls -a /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts
.  ..  .NUGGET  Asana-Math  Gyre-Pagella  Gyre-Termes  Latin-Modern  Neo-Euler  STIX-Web  TeX
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/.NUGGET
Tubular find!
The next clue is in: /usr/share/doc/python-is-python3

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ ls -a /usr/share/doc/python-is-python3
.  ..  .SECRET  changelog.gz  copyright
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/doc/python-is-python3/.SECRET
Yahaha, you found me!
The next clue is in: /usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ ls /usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel
HINT  OBJLoader2Parser.d.ts  OBJLoader2Parser.js  WorkerRunner.d.ts  WorkerRunner.js  jsm
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel$ ls -a
.  ..  HINT  OBJLoader2Parser.d.ts  OBJLoader2Parser.js  WorkerRunner.d.ts  WorkerRunner.js  jsm
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel$ cat HINT
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/drivers/staging/vt6655
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel$ ls /opt/linux/linux-5.4/drivers/staging/vt6655
Kconfig   NOTE  baseband.c  card.c  channel.c  desc.h    device_cfg.h   dpc.c  key.c  mac.c  power.c  rf.c  rxtx.c  srom.c  test      upc.h
Makefile  TODO  baseband.h  card.h  channel.h  device.h  device_main.c  dpc.h  key.h  mac.h  power.h  rf.h  rxtx.h  srom.h  tmacro.h
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel$ cat NOTE
cat: NOTE: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel$ cat /opt/linux/linux-5.4/drivers/staging/vt6655
cat: /opt/linux/linux-5.4/drivers/staging/vt6655: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/three/examples/jsm/loaders/obj2/worker/parallel$ cd /opt/linux/linux-5.4/drivers/staging/vt6655
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/staging/vt6655$ ls
Kconfig   NOTE  baseband.c  card.c  channel.c  desc.h    device_cfg.h   dpc.c  key.c  mac.c  power.c  rf.c  rxtx.c  srom.c  test      upc.h
Makefile  TODO  baseband.h  card.h  channel.h  device.h  device_main.c  dpc.h  key.h  mac.h  power.h  rf.h  rxtx.h  srom.h  tmacro.h
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/staging/vt6655$ cat NOTE
Lucky listing!
The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Latin-Modern/Operators/Regular

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/staging/vt6655$ ls -a /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Latin-Modern/Operators/Regular
.  ..  .INSIGHT  Main.js
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/staging/vt6655$ cat .INSIGHT
cat: .INSIGHT: No such file or directory
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/staging/vt6655$ cd .INSIGHT
bash: cd: .INSIGHT: No such file or directory
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/staging/vt6655$ cd /usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Latin-Modern/Operators/Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Latin-Modern/Operators/Regular$ cat .INSIGHT
Lucky listing!
The next clue is in: /usr/lib/python3/dist-packages/pkg_resources/_vendor/packaging

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Latin-Modern/Operators/Regular$ ls -a /usr/lib/python3/dist-packages/pkg_resources/_vendor/packaging
.  ..  .SPOILER  __about__.py  __init__.py  __pycache__  _compat.py  _structures.py  markers.py  requirements.py  specifiers.py  utils.py  version.py
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/jax/output/HTML-CSS/fonts/Latin-Modern/Operators/Regular$ cd /usr/lib/python3/dist-packages/pkg_resources/_vendor/packaging
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/pkg_resources/_vendor/packaging$ cat .SPOILER
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{MvnGnSWwudNJHU-CWBFGzb2KFmp.dljM4QDL5kDN0czW}
```
## Learning:
 I learnt how to use cd,ls,cat and other commands more properly in linux
## References:
 did on my own
