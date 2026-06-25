# One Dark Pro for Zed

A faithful [Zed](https://zed.dev) port of the popular VS Code [**One Dark Pro**](https://github.com/Atom/one-dark-syntax) theme.

Zed ships a built-in *One Dark*, but it uses a muted, greyed-out palette (`#3b414d` background, desaturated `#74ade8` blue). This extension restores the original One Dark Pro look: the deep `#282c34` editor background and the vivid Atom One Dark hues, plus italic comments.

## Variants

| Theme | Editor background |
|---|---|
| **One Dark Pro** | `#282c34` |
| **One Dark Pro Darker** | `#21252b` (darker chrome and editor) |

## Palette

| Role | Color | |
|---|---|---|
| Foreground | `#abb2bf` | mono |
| Comments *(italic)* | `#5c6370` | mono-3 |
| Keywords / storage | `#c678dd` | purple |
| Functions / methods | `#61afef` | blue |
| Strings | `#98c379` | green |
| Variables / tags / properties | `#e06c75` | red |
| Numbers / constants / attributes | `#d19a66` | orange |
| Classes / types | `#e5c07b` | yellow |
| Operators / escapes / regex | `#56b6c2` | cyan |
| Cursor / accent | `#528bff` | blue |

## Install

### From the Zed extension registry

Open the command palette → `zed: extensions`, search for **One Dark Pro**, and click Install. Then `theme selector: toggle` and pick *One Dark Pro* or *One Dark Pro Darker*.

### As a dev extension (local)

Clone this repo, then in Zed run `zed: install dev extension` and select the cloned folder. Zed compiles and loads it immediately; changes to `themes/one-dark-pro.json` hot-reload.

```bash
git clone https://github.com/Alivers/zed-one-dark-pro
```

## License

MIT. Theme colors derive from Atom's One Dark, MIT-licensed by GitHub.
