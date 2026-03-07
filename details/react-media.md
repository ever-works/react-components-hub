## Overview

React Media provides a declarative way to handle responsive design in React by using CSS media queries to conditionally render components based on the current viewport size or device characteristics.

## Features

- CSS media query support
- Component-based API
- Render props pattern
- Hook API
- Server-side rendering support
- Multiple queries
- Custom queries
- Breakpoint matching
- Device detection
- Orientation detection
- TypeScript support

## Query Support

- min-width / max-width
- min-height / max-height
- orientation (portrait/landscape)
- aspect-ratio
- resolution
- hover capability
- pointer type
- Any CSS media query

## API Patterns

### Component API
- Media component
- query prop
- render prop
- children function

### Hook API
- useMedia() hook
- Boolean match result
- Multiple queries

## Common Patterns

### Responsive Components
- Mobile vs desktop layouts
- Different navigation on mobile
- Conditional sidebars
- Responsive images
- Mobile-specific features

### Breakpoint Management
- Small screens
- Medium screens
- Large screens
- Extra large screens
- Custom breakpoints

### Device Detection
- Mobile devices
- Tablets
- Desktops
- Touch vs mouse
- Retina displays

## SSR Support

- Default values for SSR
- Server-side media queries
- Hydration handling
- No flash of wrong content

## Performance

- Native matchMedia API
- Efficient re-renders
- Event-based updates
- No polling
- Cleanup on unmount

## Use Cases

- Responsive layouts
- Conditional feature loading
- Mobile-first design
- Progressive enhancement
- Adaptive images
- Navigation menus
- Modal vs drawer on mobile
- Different data tables

## Integration

- Works with CSS-in-JS
- Styled-components compatible
- Tailwind CSS breakpoints
- Bootstrap breakpoints
- Custom design systems

## Pricing

Free and open-source under the MIT license.