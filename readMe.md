# Hyprland Config Setup

Install these packages first so this config works across desktops and laptops.

## Core packages (required)

### Arch / Endeavour / Garuda
```bash
sudo pacman -S \
  hyprland hyprlock hypridle \
  xdg-desktop-portal-hyprland xdg-desktop-portal-gtk \
  waybar mako fuzzel nwg-drawer \
  alacritty thunar pavucontrol playerctl \
  hyprshot hyprpicker wl-clipboard brightnessctl grim slurp \
  ttf-hack-nerd noto-fonts-emoji
```

### Debian / Ubuntu
```bash
sudo apt update
sudo apt install \
  hyprland hyprlock hypridle \
  xdg-desktop-portal-hyprland xdg-desktop-portal-gtk \
  waybar mako-notifier fuzzel nwg-drawer \
  alacritty thunar pavucontrol playerctl \
  hyprshot hyprpicker wl-clipboard brightnessctl grim slurp \
  fonts-hack fonts-noto-color-emoji
```

### Fedora
```bash
sudo dnf install \
  hyprland hyprlock hypridle \
  xdg-desktop-portal-hyprland xdg-desktop-portal-gtk \
  waybar mako fuzzel nwg-drawer \
  alacritty thunar pavucontrol playerctl \
  hyprshot hyprpicker wl-clipboard brightnessctl grim slurp \
  google-noto-color-emoji-fonts
```

### openSUSE Tumbleweed
```bash
sudo zypper install \
  hyprland hyprlock hypridle \
  xdg-desktop-portal-hyprland xdg-desktop-portal-gtk \
  waybar mako fuzzel nwg-drawer \
  alacritty thunar pavucontrol playerctl \
  hyprshot hyprpicker wl-clipboard brightnessctl grim slurp \
  symbols-only-nerd-fonts google-noto-coloremoji-fonts
```

> If a package name differs on your distro, search with your package manager and install the equivalent package.
> This config expects a Nerd Font (Hack Nerd Font recommended) for icon glyphs in lockscreen/bar apps.
> On openSUSE, `symbols-only-nerd-fonts` is usually enough for glyphs; install full Hack Nerd Font if you want full font coverage.
> If your distro does not package Hack Nerd Font directly, download `Hack.zip` from https://www.nerdfonts.com/font-downloads and install at least `HackNerdFont-Regular.ttf`.

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
