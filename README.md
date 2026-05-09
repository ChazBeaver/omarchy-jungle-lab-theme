# Jungle-Lab for Omarchy

Jungle-Lab is an Omarchy theme package built to coordinate the wider desktop theme with the Neovim theme **`jungle-lab`**.

This repo is the Omarchy-side theme bundle. It provides the files Omarchy uses for desktop and application styling, while Neovim itself is styled by the separate Neovim colorscheme named `jungle-lab`.

## Relationship to the Neovim theme

This Omarchy theme is designed to pair with the Neovim theme:

- **Neovim theme name:** `jungle-lab`
- **Omarchy theme repo:** `omarchy-jungle-lab-theme`

This keeps the theme stack clean:

- Omarchy repo = desktop/app theme assets
- Neovim theme = editor colorscheme
- both are designed to complement each other

## What this repo contains

Typical files include:

- `colors.toml`
- `colors.css`
- `btop.theme`
- `cava_theme`
- `chromium.theme`
- `mako.ini`
- `walker.css`
- `warp.yaml`
- `palette.json`

## How it works with Omarchy

Omarchy uses the files here to apply the broader theme. Neovim is expected to use the `jungle-lab` colorscheme directly.

## Naming convention

- **Omarchy repo:** `omarchy-jungle-lab-theme`
- **Neovim theme:** `jungle-lab`

## Goal

Jungle-Lab is meant to provide a coordinated system theme where Neovim visually belongs to the same environment as the rest of Omarchy.
