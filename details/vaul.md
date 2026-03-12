## Overview

Vaul is a free, open-source, unstyled drawer component for React that provides a native app-like experience for mobile and tablet devices. Created by Emil Kowalski, it's built on top of Radix UI's Dialog primitive to ensure accessibility and proper keyboard navigation.

## Features

- **Lightweight**: 184 kB npm package with minimal dependencies
- **Snap Points**: Support for multiple snap positions
- **Nested Drawers**: Ability to nest drawers within drawers
- **Controlled State**: Full control over drawer open/closed state
- **Drag Handle**: Accessible drag handle for touch devices
- **Portal Support**: Renders content to document body for proper stacking
- **Overlay**: Optional overlay for modal behavior
- **Keyboard Navigation**: Full keyboard accessibility support
- **TypeScript**: Built with TypeScript for type safety

## Components

- `Drawer.Root`: Core wrapper for controlled/uncontrolled drawers
- `Drawer.Trigger`: Button to open the drawer
- `Drawer.Portal`: Portals content to the body
- `Drawer.Overlay`: Optional overlay for modal behavior
- `Drawer.Content`: Main drawer content container
- `Drawer.Handle`: Accessible drag handle
- `Drawer.Title`: Accessible title element
- `Drawer.Description`: Accessible description element

## Integration

Vaul is used in production by Vercel and powers the drawer component in shadcn/ui. It can be combined with Dialog components to create responsive interfaces that show dialogs on desktop and drawers on mobile.

## Pricing

Free and open-source under the MIT license.