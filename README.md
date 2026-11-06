# Catppuccin for docsify

A [Catppuccin](https://catppuccin.com/palette) colour scheme for [docsify](https://docsify.js.org) v5, in Latte and Mocha.

It is **not a theme**: it only sets CSS variables read by docsify's own core styles, so layout and decoration are left alone. Pair it with any docsify theme.

Demo: <https://kemiamu.github.io/docsify-catppuccin/>

## Usage

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/docsify@5/dist/themes/core.min.css">
<link rel="stylesheet" href="//kemiamu.github.io/docsify-catppuccin/catppuccin-latte.css" media="(prefers-color-scheme: light)">
<link rel="stylesheet" href="//kemiamu.github.io/docsify-catppuccin/catppuccin-mocha.css" media="(prefers-color-scheme: dark)">
```

Keep one line for a single flavour. jsDelivr alternative:

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

## License

[MIT](LICENSE) © kemiamu
