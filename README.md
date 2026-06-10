# Tokyo Day for Omarchy

Tokyo Day is a soft light theme for [Omarchy](https://omarchy.org/) inspired by Tokyo Night, translated into a calm daytime palette: paper-light backgrounds, Tokyo blue accents, sakura pink highlights, and muted ink text.

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
background  #f7f1ea
surface     #eee6dc
foreground  #2d3046
muted       #75778b
tokyo blue  #3b64c4
sakura pink #d86aa7
yellow      #9c6835
cyan        #2e7d8f
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

Included wallpapers:

- `TokyoDay1.png`
- `TokyoDay2.png`
- `TokyoDay3.jpg`

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
