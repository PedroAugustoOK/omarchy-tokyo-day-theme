# Tokyo Day for Omarchy

Tokyo Day is a soft light theme for [Omarchy](https://omarchy.org/) inspired by Tokyo Night, translated into a sakura daytime palette: paper-light backgrounds, Tokyo blue accents, warm flower pink, muted ink text, and layered surfaces for a light theme that does not feel flat.

It is designed to avoid the usual light-theme problems: pure white backgrounds, harsh black text, incomplete app coverage, and wallpapers that fight the UI.

## Preview

![Tokyo Day preview](preview.png)

## Install

Install and apply with Omarchy:

```bash
omarchy theme install https://github.com/PedroAugustoOK/omarchy-tokyo-day-theme.git
```

The Omarchy installer will clone this repo as:

```text
~/.config/omarchy/themes/tokyo-day
```

## Palette

```text
background    #f7f1ea
surface       #fffaf4
surface-2     #eee6dc
surface-3     #e4d9d0
foreground    #2d3046
muted         #75778b
tokyo blue    #3b64c4
sakura pink   #d86aa7
yellow        #9c6835
cyan          #2e7d8f
```

## Depth model

Tokyo Day uses a soft layered model rather than pure-white contrast:

```text
wallpaper processed with a light paper wash
base background for the desktop
surface cards for launchers and notifications
subtle borders to separate layers
blue for focus and selection
pink for emotional highlights and urgent accents
warm shadows for depth without dark-mode heaviness
```

## Included

```text
colors.toml
waybar.css
hyprland.conf
hyprlock.conf
walker.css
mako.ini
icons.theme
light.mode
alacritty.toml
foot.ini
ghostty.conf
kitty.conf
btop.theme
gtk.css
swayosd.css
neovim.lua
vscode.json
zed.json
backgrounds/
```

## Wallpapers

Original wallpapers live in:

```text
backgrounds/
```

Desktop-friendly processed variants live in:

```text
backgrounds/processed/
```

The processed variants are cropped to 16:9 and softened with a light paper wash so the bar, launcher, and window borders remain readable.

## Development

This repo is intentionally only the theme package. Personal Omarchy overrides, keybinds, AppImage helpers, and custom Waybar scripts are not included.

To test local changes after cloning:

```bash
mkdir -p ~/.config/omarchy/themes
rm -rf ~/.config/omarchy/themes/tokyo-day
cp -a . ~/.config/omarchy/themes/tokyo-day
omarchy theme set tokyo-day
```

## License

MIT
