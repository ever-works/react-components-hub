## Overview

React Input Mask is an input masking component for React applications made with careful attention to user experience. It helps prevent transcription errors and provides user-friendly input constraints.

## Features

- **Flexible Masks**: Support for various input formats
- **UX-Focused**: Designed for optimal user experience
- **Custom Format Characters**: Define your own format rules
- **Dynamic Masks**: Change mask based on input
- **Copy/Paste Support**: Handles paste events intelligently
- **React 16.8+**: Modern React support
- **TypeScript**: Type definitions included

## Default Format Characters

- `9`: Digits 0-9
- `a`: Letters A-Z, a-z
- `*`: Alphanumeric (A-Z, a-z, 0-9)
- Custom characters can be defined

## Common Use Cases

### Phone Numbers
```
(999) 999-9999
+1 (999) 999-9999
```

### Dates
```
99/99/9999
99-99-9999
```

### Credit Cards
```
9999 9999 9999 9999
9999-9999-9999-9999
```

### Social Security
```
999-99-9999
```

### Custom Formats
Any pattern using format characters

## Configuration

- Mask pattern string
- Format characters object
- Mask character (placeholder)
- Always show mask toggle
- Before mask state change callback

## Behavior

- Automatic formatting as user types
- Cursor position management
- Backspace/delete handling
- Paste event processing
- Placeholder support

## Integration

Works as a drop-in replacement for standard input elements:
```jsx
<InputMask mask="(999) 999-9999" />
```

## Accessibility

Maintains standard input accessibility features with proper ARIA support.

## Browser Support

All modern browsers including IE11.

## Pricing

Free and open-source under the MIT license.