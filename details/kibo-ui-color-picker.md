## Overview

The Kibo UI Color Picker is a component in Kibo UI designed for selecting colors in a UI, modeled after the picker in Figma. It provides a powerful, polished color-picker component for React + Tailwind projects, fitting well with modern UI stacks and the broader Kibo UI component ecosystem.

## Features

- Figma-inspired color picker UI
- Alpha/transparency support
- Rich feature set with high customizability
- Part of broader Kibo UI component ecosystem
- shadcn/ui compatible design
- Copy-and-paste installation

## Installation

```bash
npx kibo-ui add color-picker
```

```tsx
import { ColorPicker } from 'kibo-ui/components/color-picker';
const [color, setColor] = useState<string>('#ff0000');
<ColorPicker
  value={color}
  onChange={setColor}
  showAlpha={true}
/>
```

## Use Cases

- Theme customization interfaces
- Design tool components
- Color selection in forms and settings
- Integration with other Kibo UI components

## Themes

Supports CSS variable-based theming:

```css
:root {
  --primary: #ff0000;
}
.dark {
  --primary: #1a75ff;
}
```