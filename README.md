# MTI Premium Theme

A premium design theme for the MTI SaaS product: "Oxford ink and champagne".

- `theme/mti-theme.css` holds the design tokens (color, type, spacing, radius, elevation) and ready-made components: buttons, inputs, selects, switches, cards, badges, tables, navigation, tabs, avatars, progress bars and toasts.
- `index.html` is a live showcase: a sample dashboard plus the theme kit.

## Use it

```html
<link rel="stylesheet" href="theme/mti-theme.css">
<button class="mti-btn mti-btn--primary">Save changes</button>
```

## Palette

| Token | Light | Dark |
|---|---|---|
| `--primary` | `#121A2E` Oxford ink | `#D8B878` champagne |
| `--accent` | `#A8823F` champagne | `#D8B878` |
| `--bg` | `#F5F6F8` | `#0A0D15` |
| `--surface` | `#FFFFFF` | `#111623` |
| `--text` | `#121A2E` | `#EDEFF4` |

Typefaces: **Instrument Serif** for display figures and headlines, **Geist** for UI text, **Geist Mono** for numbers and IDs.

## Dark mode

Dark mode follows the OS setting automatically. To force a theme, set `data-theme="dark"` or `data-theme="light"` on `<html>`.
