# Hyprland Config Setup

Install these packages first so this config works across desktops and laptops.

## Core packages (required)

### Arch / Endeavour / Garuda
```bash
sudo pacman -S hyprland hyprlock hypridle xdg-desktop-portal-hyprland xdg-desktop-portal-gtk waybar mako fuzzel nwg-drawer alacritty thunar pavucontrol playerctl hyprshot hyprpicker wl-clipboard brightnessctl grim slurp ttf-hack-nerd noto-fonts-emoji
```

### Debian / Ubuntu
```bash
sudo apt update
sudo apt install hyprland hyprlock hypridle xdg-desktop-portal-hyprland xdg-desktop-portal-gtk waybar mako-notifier fuzzel nwg-drawer alacritty thunar pavucontrol playerctl hyprshot hyprpicker wl-clipboard brightnessctl grim slurp fonts-hack fonts-noto-color-emoji
```

### Fedora
```bash
sudo dnf install hyprland hyprlock hypridle xdg-desktop-portal-hyprland xdg-desktop-portal-gtk waybar mako fuzzel nwg-drawer alacritty thunar pavucontrol playerctl hyprshot hyprpicker wl-clipboard brightnessctl grim slurp google-noto-emoji-fonts
```

### openSUSE Tumbleweed
```bash
sudo zypper install hyprland hyprlock hypridle xdg-desktop-portal-hyprland xdg-desktop-portal-gtk waybar mako fuzzel nwg-drawer alacritty thunar pavucontrol playerctl hyprshot hyprpicker wl-clipboard brightnessctl grim slurp
```

> If a package name differs on your distro, search with your package manager and install the equivalent package.

## Optional apps referenced by keybinds

```bash
brave obsidian signal-desktop telegram-desktop zed
```

## Customization

Use the clone helper script:

```bash
./scripts/cloneConfigs.sh
```

This script clones app configs and wallpapers.

