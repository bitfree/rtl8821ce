# Realtek RTL8821CE Driver

## Intent
This repository hosts the code for the [ArchLinux AUR Package](https://aur.archlinux.org/packages/rtl8821ce-dkms-git/). It's targetting Linux > 4.14 and is being developed for ArchLinux. No support will be provided for other Linux distributions or Linux Kernel versions outside of that range. 

## DKMS
This driver can be installed using [DKMS](http://linux.dell.com/dkms/). This is a system which will automatically recompile and install a kernel module when a new kernel gets installed or updated. To make use of DKMS, install the `dkms` package.


## Installation of Driver
In order to install the driver open a terminal in the directory with the source code and execute the following command:
```
sudo ./dkms-install.sh
```

## Removal of Driver
In order to remove the driver from your system open a terminal in the directory with the source code and execute the following command:
```
sudo ./dkms-remove.sh
```

