SL-Random: Cure your bad habit of mistyping, with a twist!
=======================================

SL (Steam Locomotive) runs across your terminal when you type "sl" as
you meant to type "ls". It's just a joke command, and not useful at
all.

Copyright 1993,1998,2014 Toyoda Masashi (mtoyoda@acm.org)

SL-random changes the number of drawn carriages to be anywhere from 0 to 20 (inclusive). You can download the newest version from the releases page.
If you wish to build it yourself, use the following bash commands:
```
git clone https://github.com/peterw18/sl-random
cd sl-random
make
```
Alternatively, patch your original sl binary from https://github.com/mtoyoda/sl:
```
sudo apt install bsdiff
mv sl sl-temp
sudo bspatch sl-temp sl sl-random.patch
```

Copyright 2025 Peter Walker (peterjw2005@gmail.com)

![](demo.gif)
