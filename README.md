# StyleShift Tailwind Presets

A Tailwind CSS preset that provides semantic colors, optimized defaults, and essential plugins.

## Features

- 🧩 Essential Tailwind plugins pre-configured
- 🎨 Semantic color system with dark mode support
- 🔤 Optimized typography with Roboto font families
- 🌗 Dark mode support via className strategy

## Usage

### Configure Tailwind

Add the preset to your `tailwind.config.ts`:

```typescript
import styleshift from "@styleshift/preset";

export default {
  presets: [styleshift],
};
```

Add the Roboto fonts:

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&family=Roboto+Serif:ital,opsz,wght@0,8..144,100..900;1,8..144,100..900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap"
  rel="stylesheet"
/>
```

## Features

### Fonts

The preset provides Roboto font with `font-sans`, `font-serif` and `font-mono`.

### Colors

The preset provides semantic color `positive`, `negative`, `warning`, `info` and `neutral`.

### Plugins

Pre-configured plugins

- [@tailwindcss/typography](https://tailwindcss.com/docs/typography-plugin) - Beautiful typographic defaults
- [@tailwindcss/forms](https://github.com/tailwindlabs/tailwindcss-forms) - Form element styling
- [@tailwindcss/aspect-ratio](https://github.com/tailwindlabs/tailwindcss-aspect-ratio) - Aspect ratio utilities
- [@tailwindcss/container-queries](https://github.com/tailwindlabs/tailwindcss-container-queries) - Container query support
