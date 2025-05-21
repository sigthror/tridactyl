<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/tridactyl/tridactyl">Tridactyl</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
  <img src="./assets/display.png"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
  <img src="./assets/screenshot-latte.png"/>
</details>
<details>
<summary>🪴 Frappé</summary>
  <img src="./assets/screenshot-frappe.png"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
  <img src="./assets/screenshot-macchiato.png"/>
</details>
<details>
<summary>🌿 Mocha</summary>
  <img src="./assets/screenshot-mocha.png"/>
</details>

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

/* Change font used throughout */
--font: monospace;

```
- Change `--rosewater` and `--lavender` to the colors you prefer.
- Change `monospace` to your preferred font, i.e. `"Fira Code"`

Available colors correspond to [Catppuccin Palette](https://catppuccin.com/palette): pink, purple, red, etc...


## Thanks
[base16-tridactyl](https://github.com/bezmi/base16-tridactyl)

[Cattpuccin Color Scheme](https://catppuccin.com)
