## Overview

Gradient Picker is a React component that allows users to select solid colors, gradients, or background images. It is designed for seamless integration into component-library/UI systems, especially with the shadcn/ui ecosystem.

## Features

- Three selection modes: Solid colors, Gradients, and Images
- Pre-built color swatches for quick selection
- Pre-built gradient presets with multiple directions
- Background image support with Unsplash integration
- Popover-based UI for compact integration
- Uses shadcn/ui primitives: Button, Input, Popover, Tabs
- Customizable via className prop
- Live preview of selected background

## Installation

Requires shadcn/ui components:
```bash
npx shadcn-ui@latest add tabs button input popover
```

```tsx
export function PickerExample() {
  const [background, setBackground] = useState('#B4D455')
  return (
    <GradientPicker background={background} setBackground={setBackground} />
  )
}
```

## Use Cases

- Background customization in design tools
- Hero section and card styling
- Theme builder applications
- Visual editors for web applications