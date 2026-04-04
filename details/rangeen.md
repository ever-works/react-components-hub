## Overview

Rangeen is an open-source tool for creating color palettes for websites, especially suited to projects using the shadcn/ui and Tailwind CSS ecosystem. It lets users pick colors, visualize them, and generate theme files or palettes that can be dropped directly into their UI system.

## Features

- Visual color palette generation
- Real-time color preview and visualization
- Generates ready-to-use theme files
- Tailwind CSS config output integration
- Supports shadcn/ui token system (--primary, --background, etc.)
- Dark mode color variant generation
- 10-shade palette generation per brand color

## Installation

```bash
git clone https://github.com/navnote/rangeen.git
cd rangeen
npm install
npm run dev
```

## Generated Output Example

```js
// tailwind.config.js
module.exports = {
  theme: {
    extend: {
      colors: {
        brand: {
          50: '#f5f9ff',
          100: '#e1edff',
          500: '#1a75ff',
          900: '#001c51',
        },
      },
    },
  },
}
```

Use in your app:
```css
bg-brand-500
text-brand-700
```

## Use Cases

- Brand color palette generation
- Design system creation
- shadcn/ui theme file generation
- Visual palette prototyping for web projects