## Overview

Jolly UI's Color Picker is a flexible, accessible color-selection UI built on React + Tailwind + React Aria Components. It allows selecting colors in various color spaces with optional sliders and eyedropper support, designed specifically for the shadcn/ui ecosystem.

## Features

- Support for multiple color spaces: Hex, HSL, RGB
- Color sliders for intuitive selection
- Eyedropper support for picking colors from the screen
- Built with React Aria Components for accessibility
- shadcn/ui-compatible design
- Copy-and-paste component integration
- Customizable via Tailwind CSS

## Installation

```bash
npx shadcn@latest add https://jollyui.dev/default/color
```

```tsx
import { ColorPicker, ColorPickerStateContext } from 'jollyui/components/color';

function MyPicker() {
  const [color, setColor] = useState('#ff0000');
  return (
    <ColorPicker
      value={color}
      onChange={setColor}
      // optionally include sliders, eyedropper etc
    />
  );
}
```

## Eyedropper Integration

```tsx
if (typeof EyeDropper === 'undefined') {
  return null;
}
new EyeDropper().open().then((result) => {
  state.setColor(parseColor(result.sRGBHex));
});
```

## Use Cases

- Theme editors and brand customization tools
- Accessible color selection in forms and settings panels
- Design system tools within shadcn/ui-based applications