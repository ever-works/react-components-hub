## Overview

shadcn-color-picker is a React component built on top of react-colorful, designed to integrate smoothly with the shadcn/ui ecosystem using Tailwind, CSS variables, and component-library conventions. It provides a minimal UI for color selection.

## Features

- Built on react-colorful library
- Minimal, streamlined UI for color selection
- shadcn/ui ecosystem integration
- CSS variable theming support (--primary, --primary-foreground)
- Tailwind CSS compatible
- Works with light and dark modes

## Installation

```tsx
import { ColorPicker } from 'shadcn-color-picker';
const [color, setColor] = useState('#ff0000');
<ColorPicker value={color} onChange={setColor} />
```

## Theming

Supports CSS variable-based theming:

```css
:root {
  --primary: #ff0000;
}
.dark {
  --primary: #1a75ff;
}
```

Use the color in your UI components:
```tsx
<button className="bg-primary text-primary-foreground">Click me</button>
```

## Use Cases

- Simple color selection in forms and settings panels
- shadcn/ui theme configuration
- Lightweight color picker integration in projects already using react-colorful
- Brand color customization interfaces