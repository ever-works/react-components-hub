## Overview

Raily Dev's Shadcn UI Customizer is a visual theme-customization tool built for the shadcn/ui component library. It allows users to change color tokens, typography, and other design variables through interactive color pickers and live previews, then produces a ready-to-use theme for their project.

## Features

- Interactive color pickers for modifying color tokens
- Typography configuration
- Real-time live preview of theme changes
- One-click theme generation
- Produces ready-to-install themes via shadcn CLI
- Supports all shadcn/ui theme variables (--primary, etc.)
- Dark mode configuration support

## Installation

Generated themes can be installed via:
```bash
npx shadcn add <theme-url>
```

Or manually added to `tailwind.config.js`:
```css
:root { --primary: … }
```

## Use Cases

- Rapid theme prototyping for shadcn/ui projects
- Non-technical visual customization of component libraries
- Theme sharing and distribution
- Design-to-development handoff workflows