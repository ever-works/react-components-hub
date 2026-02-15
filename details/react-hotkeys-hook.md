## Overview

React Hotkeys Hook makes it simple to add keyboard shortcuts to React applications with a hook-based API and no complex setup.

## Key Features

- **Hook-Based API**: Simple import and use
- **Modifier Keys**: Support for Ctrl, Shift, Alt, Meta
- **Multiple Keys**: Combine multiple keys
- **Platform-Specific**: Different shortcuts for Mac/Windows
- **Focus Scoping**: Only active when focus is correct
- **TypeScript Support**: Fully typed
- **SSR Compatible**: Works with server-side rendering
- **No Dependencies**: Lightweight and fast

## Basic Usage

```jsx
const { handlers } = useHotkeys('ctrl+k', () => {
  console.log('Ctrl+K pressed')
})
```

## Features

- **Global Shortcuts**: Define application-wide hotkeys
- **Component-Scoped**: Limit to specific components
- **Combination Keys**: Ctrl+Shift+S, Cmd+K, etc.
- **Platform Detection**: Auto-detect Mac vs Windows
- **Active/Inactive**: Enable/disable hotkeys
- **Multiple Handlers**: Bind multiple callbacks
- **Event Prevention**: Prevent default behavior

## Common Use Cases

- Command Palette (Cmd/Ctrl+K)
- Search Activation (Cmd/Ctrl+F)
- Navigation Shortcuts
- Global Actions (Save, Delete, etc.)
- Modal Shortcuts (ESC to close)

## Pricing

Free and open-source under the MIT license.