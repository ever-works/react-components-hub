## Overview

React Full Screen is a React component that provides fullscreen functionality using the browser's Fullscreen API, normalized with fscreen for cross-browser compatibility.

## Features

- Uses the native Fullscreen API
- Cross-browser compatible via fscreen
- React hooks support with `useFullScreenHandle()`
- Enter/exit methods
- Active state tracking
- Event callbacks (onChange)
- User-initiated requirement (onClick, etc.)
- TypeScript support
- Works with any React component as children
- Escape key to exit fullscreen
- Responsive to browser fullscreen changes

## Usage Pattern

- Fullscreen must be triggered by user action (onClick)
- Provides handle with enter/exit methods
- Track fullscreen state
- Handle fullscreen changes

## Use Cases

- Video players
- Image galleries
- Presentation modes
- Game interfaces
- Dashboard views
- Focus modes
- Media viewers

## Pricing

Free and open-source under the MIT license.