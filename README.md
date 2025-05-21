# catppuccin-tridactyl

Catppuccin theme for Tridactyl

## Install
`:colourscheme --url https://raw.githubusercontent.com/devnullvoid/catppuccin-tridactyl/main/catppuccin-<flavor>.css catppuccin-<flavor>`

## Customization
- Fork the repo
- Edit CSS vars to change colors/font to your preference
- Use `:colourscheme --url https://raw.githubusercontent.com/<user>/catppuccin-tridactyl/main/catppuccin-<flavor>.css catppuccin-<flavor>_custom` command to set your custom theme

### Example: 

```css
/* Changing color assigned to CSS Variable */
--tridactyl-url-fg: var(--rosewater);
--tridactyl-border: var(--lavender);
```
Change `--rosewater` and `--lavender` to the colors you prefer.

Available colors correspond to [Catppuccin Palette](https://catppuccin.com/palette): pink, purple, red, etc...

Change the font:

`--font: monospace;` Change to `--font: "FiraCode Nerd Font Mono";`

## Credit
[base16-tridactyl](https://github.com/bezmi/base16-tridactyl)

[Cattpuccin Color Scheme](https://catppuccin.com)
