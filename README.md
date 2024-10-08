# WSL2-Linux-Kernel-Builder
![kernel-build](https://github.com/narrator-z/WSL2-Linux-Kernel-Builder/actions/workflows/build.yml/badge.svg)

This adds USB (usbip) and USB-CAN support to WSL2 Kernel.

+ Download one of the [Kernels](https://github.com/narrator-z/WSL2-Linux-Kernel-Builder/actions) (click the latest workflow run)
+ Create a `.wslconfig` file on `/mnt/c/Users/<user>/` and add a reference to the created image with the following.[^1]
    ```ini
    [wsl2]
    kernel=c:\\users\\<user>\\linux-msft-wsl-5.10.y-usbip-can
    ```

[^1]: [usbipd-win](https://github.com/dorssel/usbipd-win)
