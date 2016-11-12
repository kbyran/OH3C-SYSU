# OH3C
用于中山大学东校区的 OpenWrt H3C 802.1x 认证客户端 - H3C 802.1x Client for OpenWrt in SYSU East Campus

## Environment
* OpenWrt
* Python2

## Installation
Two installation methods available:

* (Recommend) Download the compiled package we provided and install.

    [`oh3c_2016_11_12.ipk`](https://raw.githubusercontent.com/kbyran/OH3C/dl/downloads/oh3c_2016_11_12.ipk)
    
    [`python-mini-oh3c-md5_2.6.4-4_ramips.ipk`](https://raw.githubusercontent.com/kbyran/OH3C/dl/downloads/python-mini-oh3c-md5_2.6.4-4_ramips.ipk)
    
* Directly copy files in master branch to the \usr. 

We also release compile files to build packages for your own OpenWrt machine. See details in [Wiki](https://github.com/kbyran/OH3C/wiki)!

## How to use

`oh3c` works! 

To enable self-starting, `vi /etc/rc.local`

> \# Put your custom commands here that should be executed once

> \# the system init finished. By default this file does nothing.

> \# echo 3|oh3c stands for autorunning the third identity in oh3c.

> echo 3|oh3c

> exit 0

## Thanks

* [nanpuyue/OH3C](https://github.com/nanpuyue/OH3C): We base on the implementation.

* [zlsun/yah3c](https://github.com/humiaozuzu/YaH3C): Privide m5d method.
