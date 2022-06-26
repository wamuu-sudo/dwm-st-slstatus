## Dwm install by Hyda (Arch, Endeavour, Gentoo)

0/ Download & extract dwm-blue

1/ Paste the .xinit.rc in your /home/$user (some modifications are required, like the link of your wallpaper, & the path of screenadjust & noafk)

2/ Install picom
```pacman -S picom```

3/ Paste picom.conf in your /home/$user/.config

4/ Install feh
```pacman -S feh```
    And modify if not already yet your feh path in the previous .xinit.rc

5/ Modify the slstatus/config.h (wifi card to change)

6/ Download & install nerd-fonts on github.com/ryanoasis/nerd-fonts
    ```sh install.sh```

7/ Install dwm
    For each folder dmenu, st, slstatus & dwm
    ``` sudo make ```
    ``` sudo make install ```

8/ Reboot & choose Dwm on your login connection (slim is advised)

# Keyboard
Win+shift+Enter : terminal
Win+Shift+C : ferme la fenêtre où tu as le focus
Win+p : dmenu (pour lancer c'est progs) équivalent à Krunner
Win+Shift+q : Arrêt forcé de dwm
