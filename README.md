# One Dark Pro for Zed

A faithful [Zed](https://zed.dev) port of the popular VS Code [**One Dark Pro**](https://github.com/Atom/one-dark-syntax) theme.

Zed ships a built-in *One Dark*, but it uses a muted, greyed-out palette (`#3b414d` background, desaturated `#74ade8` blue). This extension restores the original One Dark Pro look: the deep `#282c34` editor background and the vivid Atom One Dark hues, plus italic comments.

## Variants

All five official variants are ported, with each variant's exact backgrounds, cursor, and italic settings taken from the upstream VS Code theme files:

| Theme | Editor bg | Chrome | Notes |
|---|---|---|---|
| **One Dark Pro** | `#282c34` | `#21252b` | the original; italic comments & params |
| **One Dark Pro Darker** | `#23272e` | `#1e2227` | dimmer, italics off |
| **One Dark Pro Flat** | `#282c34` | `#282c34` | uniform background, white cursor, italics off |
| **One Dark Pro Mix** | `#282c34` | `#21252b` | flat editor + darker activity/title bar |
| **One Dark Pro Night Flat** | `#16191d` | `#16191d` | darkest, flat, italics off |

Only the standard *One Dark Pro* ships italics (comments, parameters, `super`/`this`, markdown emphasis) — exactly as upstream does.

## Palette

| Role | Color | |
|---|---|---|
| Foreground / operators / punctuation | `#abb2bf` | mono |
| Comments | `#7f848e` | mono (italic in standard) |
| Keywords / storage | `#c678dd` | purple |
| Functions / methods | `#61afef` | blue |
| Strings / regex literals | `#98c379` / `#e06c75` | green / red |
| Variables / tags / properties / headings | `#e06c75` | red |
| Numbers / constants / booleans / attributes | `#d19a66` | orange |
| Classes / types / `this` / namespaces | `#e5c07b` | yellow |
| Escapes / operators-special / enum members | `#56b6c2` | cyan |
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
