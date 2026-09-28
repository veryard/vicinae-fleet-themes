# Fleet Themes for Vicinae

Fleet's sleek, modern aesthetic for [Vicinae](https://vicinae.com),
ported from the [Fleet Themes for Zed](https://github.com/skarline/zed-fleet-themes) palettes.

## Themes

- **Fleet Dark** (`fleet-dark.toml`): dark background (`#18191B`), Fleet blue accent (`#2A7DEB`)
- **Fleet Light** (`fleet-light.toml`): white background, near-black text, Fleet blue accent

## Install / development

Symlink the themes into Vicinae's user theme directory:

```bash
ln -s "$PWD/fleet-dark.toml" ~/.local/share/vicinae/themes/
ln -s "$PWD/fleet-light.toml" ~/.local/share/vicinae/themes/
```

Vicinae watches that directory and hot-reloads changes, so edits here apply
without restarting.

Activate under Settings → Theme, or via CLI:

```bash
vicinae theme set fleet-dark
vicinae theme set fleet-light
```

## Credits

Palette source: [skarline/zed-fleet-themes](https://github.com/skarline/zed-fleet-themes)
(original Fleet color themes).
