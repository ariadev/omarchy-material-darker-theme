# Material Darker for Omarchy

An Omarchy theme based on Material Theme Darker, with matching terminal colors, LazyVim/Neovim integration, VS Code integration, icons, and wallpapers.

## Install

Publish this repository as `omarchy-material-darker-theme` so Omarchy installs it as `material-darker`:

```bash
omarchy theme install https://github.com/ariadev/omarchy-material-darker-theme.git
```

After installation, Omarchy applies the theme automatically. To switch back to it later:

```bash
omarchy theme set "Material Darker"
```

## Included

- `colors.toml` for Omarchy-generated terminal, Waybar, Hyprland, Mako, btop, and app themes
- `neovim.lua` using `marko-cerovac/material.nvim` with the `darker` style
- `vscode.json` using the `equinusocio.material-theme` extension
- `icons.theme` using `Yaru-red`
- `backgrounds/` with matching dark Material wallpapers

## Publish

From this directory:

```bash
git init
git add .
git commit -m "Add Material Darker Omarchy theme"
git branch -M main
git remote add origin git@github.com:ariadev/omarchy-material-darker-theme.git
git push -u origin main
```

## Notes

Omarchy installs a theme by cloning the repository directly into `~/.config/omarchy/themes/<theme-name>`. Keep the theme files at the repository root.
