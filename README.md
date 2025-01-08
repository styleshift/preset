# StyleShift Tailwind Presets

A Tailwind CSS preset that provides semantic colors, optimized defaults, and essential plugins.

### Usage

Add the preset to your `tailwind.config.ts`:

```typescript
import styleshift from "@styleshift/preset";

export default {
  presets: [styleshift],
};
```

Load the Roboto fonts:

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&family=Roboto+Serif:ital,opsz,wght@0,8..144,100..900;1,8..144,100..900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap"
  rel="stylesheet"
/>
```
