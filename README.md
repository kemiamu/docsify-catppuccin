# Catppuccin for docsify

Unofficial [Catppuccin](https://catppuccin.com/palette) Latte / Mocha theme for [docsify](https://docsify.js.org) v5.

Demo: <https://kemiamu.github.io/docsify-catppuccin/>

## Usage

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/docsify@5/dist/themes/core.min.css">
<link rel="stylesheet" href="//kemiamu.github.io/docsify-catppuccin/catppuccin-latte.css" media="(prefers-color-scheme: light)">
<link rel="stylesheet" href="//kemiamu.github.io/docsify-catppuccin/catppuccin-mocha.css" media="(prefers-color-scheme: dark)">
```

Drop one line if you only need a single flavour. jsDelivr alternative:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kemiamu/docsify-catppuccin@main/catppuccin-mocha.css">
```

## Customize

```css
:root {
  --theme-color: #89b4fa; /* mauve -> blue */
}
```

See the comments in each CSS file for the rest.

## Files

| File | Description |
| --- | --- |
| `catppuccin-latte.css` | Light flavour |
| `catppuccin-mocha.css` | Dark flavour |
| `index.html` | Demo (renders this README) |

Both files only define CSS variables; no layout or decoration overrides.

## License

[MIT](LICENSE) © kemiamu
