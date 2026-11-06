# Catppuccin for docsify

[Catppuccin](https://catppuccin.com/palette) 的 **Latte** 与 **Mocha** 两套 flavour，适用于 [docsify](https://docsify.js.org) v5。

非官方移植（unofficial port）。本项目以 MIT 授权发布。

演示页：<https://kemiamu.github.io/docsify-catppuccin/>

## 用法

只需要引入 docsify 官方主题，再按系统偏好加载对应的 flavour：

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/docsify@5/dist/themes/core.min.css">
<link rel="stylesheet" href="//kemiamu.github.io/docsify-catppuccin/catppuccin-latte.css" media="(prefers-color-scheme: light)">
<link rel="stylesheet" href="//kemiamu.github.io/docsify-catppuccin/catppuccin-mocha.css" media="(prefers-color-scheme: dark)">
```

只想要一种 flavour 就只留对应那一行。

因为是从 GitHub Pages 直出，CDN 是 `kemiamu.github.io` 本身，无需额外构建或发布步骤；想缓存更久也可以走 jsDelivr：

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kemiamu/docsify-catppuccin@main/catppuccin-mocha.css">
```

## 自定义

品牌色由一个变量控制，改一行即可换主色：

```css
:root {
  --theme-color: #89b4fa; /* 例如从 mauve 换成 blue */
}
```

其余变量含义见两个 CSS 文件内的注释（`--color-bg`、`--link-color`、`--codeblock-*`、`--sidebar-*` 等）。

## 文件

| 文件 | 说明 |
| --- | --- |
| `catppuccin-latte.css` | 浅色 flavour |
| `catppuccin-mocha.css` | 深色 flavour |
| `index.html` | 演示页（docsify 渲染本 README） |

两个文件都只定义 CSS 变量，不含任何布局或装饰覆盖。

## 许可

[MIT](LICENSE) © kemiamu
