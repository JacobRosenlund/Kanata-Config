# Kanata Config

This is my config for [Kanata](https://github.com/jtroo/kanata). I try to keep it simple and only add/change keys that genuinely add efficiency or ergonomic value to the keyboard.

### Aliases
- Symbols: `sym (tap-hold 200 200 tab (layer-toggle alternate))`
- Caps to Escape/Control: `cec (tap-hold 100 100 esc lctrl)`
- Em-dash: `em (unicode "—")`

### Layers
##### Layer 1 (Default):

Prety standard layout. Not much changed except:
- `tab` -> `@sym`
- `caps` -> `@cec`

##### Layer 2 (Symbols):

Keeps most of the same layout but substitutes:
- `grv` -> `lrld`
- Function row becomes `f13-f24`
- Number row to keypad numbers
- `-` -> `@em`
- `caps` is actually Caps-lock
- `h j k l` become arrow keys

---
### Using This Config

Just place the `config.kbd` into your Kanata dotfile location (usually `~/.config/kanata`) and follow the [Usage section](https://github.com/jtroo/kanata?tab=readme-ov-file#usage) on [Kanata's GitHub](https://github.com/jtroo/kanata) to get it running in the background.

If you are running [NixOS](https://nixos.org), copy the contents of the config, and follow [this guide](https://dev.to/shanu-kumawat/how-to-set-up-kanata-on-nixos-a-step-by-step-guide-1jkc) to set up Kanata declaratively.
