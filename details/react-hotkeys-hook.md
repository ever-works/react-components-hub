## Overview

react-hotkeys-hook is the most popular React hook for managing keyboard shortcuts declaratively. With over 2 million weekly downloads, it provides a modern, hook-based API for adding keyboard shortcuts to components.

## Features

- Hook-based API (useHotkeys)
- Scope hotkeys to components
- Ref-based element scoping
- Vim-style command sequences
- Complex keyboard combinations
- Global and local scopes
- Key collision prevention
- isHotkeyPressed function
- Modifier key support (Ctrl, Alt, Shift, Meta)
- Custom key separator
- KeyboardEvent access
- TypeScript support
- SSR compatible
- Lightweight bundle

## API

- useHotkeys(keys, callback, options): Main hook
- isHotkeyPressed(key): Check key state
- Scopes for grouping hotkeys
- preventDefault option
- enabled/disabled state
- splitKey customization

## Supported Keys

- Letter keys (a-z)
- Number keys (0-9)
- Modifier keys (ctrl, alt, shift, meta)
- Function keys (F1-F12)
- Special keys (enter, escape, space, tab, etc.)
- Arrow keys
- Custom combinations

## Scoping

- Global scope (default)
- Component-specific scopes
- Ref-based element focus
- Dynamic scope switching

## Use Cases

- Application keyboard shortcuts
- Text editor commands
- Modal keyboard navigation
- Game controls
- Accessibility shortcuts
- Power user features
- Form navigation

## Pricing

Free and open-source under the MIT license.