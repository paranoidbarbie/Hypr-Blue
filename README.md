## Rofi

![screenshot](https://github.com/paranoidbarbie/hyprland-catppuccin-latte/blob/main/assets/rofi.png)
## Waybar

![screenshot](https://github.com/paranoidbarbie/hyprland-catppuccin-latte/blob/main/assets/waybar.png)
## Neofetch and Starship Prompt

![screenshot](https://github.com/paranoidbarbie/hyprland-catppuccin-latte/blob/main/assets/neofetch.png)
## Vtop

![screenshot](https://github.com/paranoidbarbie/hyprland-catppuccin-latte/blob/main/assets/vtop.png)


## Dependencies to install

> **Nerd Fonts --** ![MesloLg & Fira Code Nerd](https://www.nerdfonts.com/font-downloads)

> waybar, dunst, hyprlock, hyprpaper, rofi

**For a seamless performance of the waybar's module please install the following packages, if already installed please skip this step**
> blueman-manager, pavucontrol, nm-connection-editor, brightnessctl, power-profiles-daemon

**Optional Dependencies
> ![cava](https://github.com/karlstav/cava)
> ![vtop](https://github.com/MrRio/vtop)

**For the starship prompt please check out my friend's repo** [![Github Badge](http://img.shields.io/badge/-Github-black?style=flat-square&logo=github&link=https://github.com/jemhv/)](https://github.com/jemhv/Cherry-Blossom/)
## Quick Shortcuts added in hyprland:
```
1. mainMod + Tab = Switch windows
2. Alt + (1, 2, 3) = swtich wallpapers
3. mainMod + B = firefox
4. mainMod + E = dolphin
5. mainMod + G = rofi
6. mainMod + L = hyprlock
7. PRINT = takes full screenshot
8. mainMod + SHIFT + PRINT = regional screenshot
```
## Quick Waybar shortcuts:
```
- Scroll up/down on brightness icon to increase/decrease brightness
- Middle click on bluetooth icons open blueman-manager > Left Click to enable and Right Click to Disable > Mousescroll toggles between on and off
- Mousescroll on volumeicon increases/decreases volume. Right click will open pavucontrol
```

# Troubleshootings

> Bluetooth is not working in waybar??

> Make sure you've installed ```bluez bluez-utils``` If you're on arch please read the guide ![Bluetooth](https://wiki.archlinux.org/title/Bluetooth). For other distribution, please check their docs.

> Sound module not working?

> Make sure you're installed ```pulseaudio``` , for arch install ``` pipewire-audio pipewire-pulse ``` and enable ```pipewire-pulse.service```

> Brightness not working??

> Please installe brightnessctl.

