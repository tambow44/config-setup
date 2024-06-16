# Setup: OpenBSD

### To Cover - %TODO

1. NeoVIM
2. minidlna
3. bash
4. gohomeserver
5. transmission
   
    i. settings.json
   
    ii. `chmod 755 /var/transmission/Downloads`

    iii. `ln -s /var/transmission/Downloads ~/Downloads`
7. gh
8. go
9. node, npm, nvm
10. /home dotfiles
    
    i. .profile, .bashrc, .config, .local, etcetc

## Desktop
1. XFCE Config
   
    i. Keyboard shortcuts, settings:
   
        * keyboard
   
        * window manager

     ii. `/usr/local/bin/xcape -e 'Super_L=Alt_L|F1;Super_R=Alt_L|F1'`

        > Install: `pkg_add xcape`

    iii. %TODO: `alwaysontop` equivalent

    iv: menulibre | config

        > Install: `pkg_add menulibre`
3. Games

    i. Gameboy

        > Install: `pkg_add mgba mgba-qt sameboy # find ROMs`

    ii. Others
   
        ```
        0ad
        0ad-data
        chessx
        gzdoom # find WADs
        hyperrogue
        lincity
        lwjgl
        megaglest
        rocksndiamonds
        supertux
        supertuxkart
        ```

5. firefox
7. thunderbird
8. ungoogled chromium (work)
9. wifi (ie bwfmm0)
    
    i. `/etc/hostname.bwfm0` :
   
        ```
        join "Flute Systems" wpakey "Team Wizard!" 
        dhcp
        ```
