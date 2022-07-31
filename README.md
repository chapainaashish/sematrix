## sematrix

Install sematrix on arch based distros
```
yay -S sematrix-plymouth-theme
```

after installation run following command
```
plymouth-set-default-theme -R sematrix
```

Note: You shold configure grub configuration file if you previously did't have used plymouth 
Refer to this [link](https://wiki.archlinux.org/title/plymouth) to configure plymouth on arch

To uninstall sematrix from system, run

```
pacman -R sematrix-plymouth-theme
```
