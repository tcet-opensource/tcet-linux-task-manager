# TCET Linux Task Manager 
TCET Linux Task Manager is a system utility to manage and monitor running processes and system resources.
TCET Linux Task Manager uses glances.

## Preview

![TCET Linux Task Manager](https://github.com/tcet-opensource/tcet-linux-assets/blob/main/tcet-linux/task-manager.png)

## Installation

###### For TCET Linux:
`sudo pacman -S tcet-linux-task-manager`

###### For Other Arch-Based Distributions:

1. Download *[PKGBUILD](https://raw.githubusercontent.com/tcet-opensource/tcet-linux-pkgbuild/main/apps/tcet-linux-task-manager/PKGBUILD)* from our pkgbuild [ repo](https://github.com/tcet-opensource/tcet-linux-pkgbuild/).

2. Run the following command where the *PKGBUILD* is located :
`makepkg -si`

##### Alternative Method To Install 
1. Download the [*tcet-linux-task-manager.\*.pkg.tar.zst*](https://github.com/tcet-opensource/tcet-linux-repo/raw/main/x86_64/tcet-linux-task-manager-23.08-3-x86_64.pkg.tar.zst) file from [tcet-linux-repo](https://github.com/tcet-opensource/tcet-linux-repo).
1. Run:
    `pacman -U tcet-linux-task-manager.*.pkg.tar.zst`

## Credits

We would like to give a sincere thanks to the [glances project](https://github.com/nicolargo/glances) without which this repo wouldn't exist. 
