# DaisyUI Themes

A collection of **custom DaisyUI themes** for Tailwind CSS projects.

This repository contains reusable DaisyUI theme files that you can freely use, modify, and distribute with attribution.

---

## Features

- Custom color palettes
- Drop-in compatible with DaisyUI
- Easy to customize and extend

---

## Installation

DaisyUI theme usage and configuration is documented in the official guide:

https://daisyui.com/docs/themes/

Below is a quick summary for common setups.

---

### Enable DaisyUI Themes

In your main CSS file enable a theme and and a theme name to the DaisyUI config:

```css
@import "tailwindcss";
@import "./themes/rosepine.css";

@plugin "daisyui" {
  themes: light --default, dark --prefersdark, rosepine;
}
```

Apply it in HTML:

```html
<html data-theme="rosepine">
```

## Contributing

Contributions are welcome:
- New themes
- Improvements
- Bug fixes

Open an issue or submit a pull request.
