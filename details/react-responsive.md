## Overview

React Responsive provides a simple way to handle responsive design in React with media query hooks and components that update when the viewport changes.

## Key Features

- **Media Query Hooks**: useMediaQuery hook
- **Component API**: Responsive component wrapper
- **Server-Side Rendering**: SSR support
- **Device Queries**: Device-specific styling
- **Orientation**: Portrait/landscape detection
- **Simplified API**: Easy to use
- **TypeScript**: Type support
- **CSS-in-JS**: Style objects supported

## Components & Hooks

- useMediaQuery: Hook-based media queries
- MediaQuery: Component wrapper
- useDevice: Device detection hook

## Features

- Breakpoint detection
- Device type detection
- Orientation detection
- Screen width detection
- Screen height detection
- DPI detection
- Print media detection
- Custom queries

## Configuration

- query: Media query string
- device: Device settings
- onChangeCapture: Change callback
- onChange: Change callback
- defaultMatches: Initial state

## Common Patterns

```jsx
const isMobile = useMediaQuery({ query: '(max-width: 600px)' })
const isTablet = useMediaQuery({ query: '(min-width: 601px) and (max-width: 1024px)' })
```

## Device Options

- tablet: Tablet detection
- mobile: Mobile detection
- browser: Browser detection
- device: Device type

## Use Cases

- Responsive Layouts
- Mobile-First Design
- Breakpoint-Based Styling
- Device Detection
- Orientation Detection
- Adaptive UI

## Pricing

Free and open-source under the MIT license.