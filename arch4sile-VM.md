# Making an Arch virtual machine for running sile

## Download an Arch ISO installer from Arch-Anywhere

https://arch-anywhere.org/  provides a good distribution that has a menu based 
installer. This makes installling the base system much easier than the one from 
arch.org

For the virtual machine I use Oracle Virtual Box. It is downloadable from
https://www.virtualbox.org/wiki/Downloads.

Create a virtual machine for Arch linux and install the downloaded ISO file into the DVD drive.

Install the Arch Linux system.

After you have rebooted into the newly installed OS

Create a user

Use these instructions to create Yaourt installer
https://www.ostechnix.com/install-yaourt-arch-linux/

now in your user account run this:

```
yaourt -Syu install sile
```

