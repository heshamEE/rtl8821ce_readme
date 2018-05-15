# rtl8821ce

This is the wifi driver cloned from:
https://github.com/endlessm/linux 

Tested on Ubuntu 16.04

For Linux kernel 4.4, use branch for_linux_4.4

For Linux kernel 4.13, checkout branch for_linux_4.13

```bash
make
sudo make install
sudo modprobe -a 8821ce
reboot
```
