## Overview

tailwind-merge is an essential utility for Tailwind CSS projects that intelligently merges class names and resolves conflicts. When two classes target the same CSS property, it keeps only the last one, preventing unexpected styling issues.

## Features

- **Conflict Resolution**: Automatically resolves conflicting Tailwind classes
- **Tailwind-Aware**: Understands Tailwind's class structure and utilities
- **Performance**: Optimized for speed with caching
- **Type-Safe**: Full TypeScript support
- **Customizable**: Configure custom Tailwind config support
- **Framework Agnostic**: Works with any framework using Tailwind
- **Small Bundle**: Minimal impact on bundle size

## How It Works

tailwind-merge analyzes Tailwind class names and identifies which CSS properties they affect. When multiple classes modify the same property, only the last one in the list is kept, following CSS cascade rules.

## Conflict Examples

- `p-4 p-6` → `p-6` (padding conflict)
- `bg-red-500 bg-blue-500` → `bg-blue-500` (background conflict)
- `text-sm text-lg` → `text-lg` (font size conflict)
- `rounded-md rounded-full` → `rounded-full` (border radius conflict)

## Common Usage Pattern

### With clsx
```javascript
import { clsx } from 'clsx'
import { twMerge } from 'tailwind-merge'

export function cn(...inputs) {
  return twMerge(clsx(inputs))
}
```

This `cn()` function is the standard pattern used in shadcn/ui and many modern React component libraries.

## Use Cases

- Component libraries with customizable classes
- Design systems with variant systems
- Conditional styling with Tailwind
- Merging default and custom classes
- Preventing accidental style conflicts
- Building reusable components

## Benefits

- Predictable styling behavior
- Easier component composition
- Reduced debugging time
- Better developer experience
- More maintainable code

## Integration

Commonly paired with clsx and class-variance-authority (CVA) to create powerful component variant systems with conflict-free class management.

## Pricing

Free and open-source under the MIT license.