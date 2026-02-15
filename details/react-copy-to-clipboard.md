## Overview

React Copy to Clipboard is a lightweight component that simplifies copying text to the clipboard with a single click, handling browser compatibility and fallbacks.

## Key Features

- **Simple API**: Single component wrapper
- **Browser Compatibility**: Works across all browsers
- **Fallback Support**: Handles older browsers
- **Custom Trigger**: Trigger on any element
- **Callbacks**: Copy success/error handlers
- **No Dependencies**: Lightweight
- **TypeScript**: Type support

## Usage

```jsx
<CopyToClipboard text="Text to copy">
  <button>Copy</button>
</CopyToClipboard>
```

## Features

- Copy plain text
- Callback on copy
- Custom button trigger
- Multiple copy elements
- Browser fallback
- Mobile support
- Accessible

## Props

- text: Text to copy
- onCopy: Success callback
- options: Copy options

## Use Cases

- Copy Links
- Copy Code
- Share Text
- Generate Coupons
- API Keys/Tokens
- Invite Links
- Reference Numbers

## Browser Support

- Modern browsers (Clipboard API)
- IE 9+ (with fallback)
- Mobile browsers

## Pricing

Free and open-source under the MIT license.