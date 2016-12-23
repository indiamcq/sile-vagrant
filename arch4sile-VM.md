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

## Create a user

* Create user
```
useradd sile
```
* Make password
```
passwd sile
```
* Swap to sile account
```
su sile
```

## Setup for Yaourt installer

Use the instructions in part 1 to create Yaourt installer
https://www.ostechnix.com/install-yaourt-arch-linux/

Now in your user account run the following without sudo:

```
yaourt -Syu install sile
```

