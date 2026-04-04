## Overview

Flexoki is an inky color scheme for prose and code, inspired by analog printing inks and warm shades of paper. It is designed for reading and writing on digital screens and offers both light and dark variants.

## Features

- Light and dark variants for digital reading/writing
- Inspired by analog printing inks and warm paper shades
- CSS variable-based color tokens
- Includes a full palette of semantic colors (base tones, reds, greens, blues, yellows, etc.)
- Designed for compatibility with shadcn/ui theme system
- Light mode paper background: #FFFCF0
- Dark mode equivalent: #1C1B1A

## Installation

Clone the repository:
```bash
git clone https://github.com/kepano/flexoki.git
```

Add CSS variables to your stylesheet:
```css
:root {
  --color-bg: #FFFCF0; /* paper light background */
  --color-base-100: #E6E4D9;
  --color-red-600: #AF3029;
  /* ... additional palette colors */
}
.dark {
  --color-bg: #1C1B1A; /* dark background */
  /* dark mode variables */
}
```

Integrate with Tailwind config:
```js
theme.extend.colors
```

Use in your app:
```css
bg-color
text-color
border-color
--background
--foreground
--primary
```

## Use Cases

- Blog and documentation site theming
- Code editor color schemes
- Reading-focused UI design
- shadcn/ui theme customization for writing environments