#### [blist](blist) or [blist_l](blist_l)
The next step in implementing batch installation scripts for Arch Linux. Now it uses a pseudo-graphic interface and makes it easy to partition and format disks.
There are some video demos: [uefi](https://www.youtube.com/watch?v=tlfbd5tCG6Y), [bios](https://www.youtube.com/watch?v=EZk5_hIgQIg). There is a version with Ukrainian localization - [blist_l](blist_l) 

In case of outdated package signatures in arch-iso, the following commands should be executed before blist script, otherwise the installation may fail
```
pacman-key --init
pacman-key --populate archlinux
pacman -S archlinux-keyring --noconfirm --needed
```

**Встановлювач Арч Лінукса на українській мові - [blist_l](blist_l)** ([demo](https://www.youtube.com/watch?v=PPibKEx33vM))
