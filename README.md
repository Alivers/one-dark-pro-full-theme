# One Dark Pro for Zed

A faithful [Zed](https://zed.dev) port of the popular VS Code theme [**One Dark Pro**](https://github.com/Binaryify/OneDark-Pro) by Binaryify. All colors are extracted directly from the upstream theme JSON files, not approximated.

Zed ships a built-in *One Dark*, but it uses a muted, greyed-out palette (`#3b414d` background, desaturated `#74ade8` blue). This extension restores the real One Dark Pro look: the deep `#282c34` editor background and the vivid One Dark Pro hues, plus italic comments on the standard variant.

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

Open the command palette → `zed: extensions`, search for **One Dark Pro**, and click Install. Then `theme selector: toggle` and pick any of the five variants.

### As a dev extension (local)

Clone this repo, then in Zed run `zed: install dev extension` and select the cloned folder. Zed compiles and loads it immediately; changes to `themes/one-dark-pro.json` hot-reload.

```bash
git clone https://github.com/Alivers/zed-one-dark-pro
```

## Credits & License

Color values are ported from [Binaryify/OneDark-Pro](https://github.com/Binaryify/OneDark-Pro) (MIT), which itself builds on Atom's One Dark syntax. This Zed port is MIT-licensed; all credit for the original theme design goes to its authors.
