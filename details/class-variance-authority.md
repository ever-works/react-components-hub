## Overview

Class Variance Authority (CVA) provides a powerful, type-safe API for building variant-based component systems. It's designed to take the pain out of managing component variants, allowing developers to focus on building great UIs.

## Features

- **Type-Safe Variants**: Full TypeScript support with autocomplete
- **Compound Variants**: Combine multiple variant conditions
- **Default Variants**: Set default values for each variant
- **Framework Agnostic**: Works with React, Vue, Svelte, and vanilla JS
- **Tailwind Optimized**: Perfect for Tailwind CSS projects
- **Small Bundle**: Minimal bundle size impact
- **Excellent DX**: Great developer experience with IntelliSense

## Variant Types

### Base Variants
Define individual variant options like size, color, or style.

### Compound Variants
Combine multiple variant conditions to create specific styling combinations.

### Default Variants
Specify default values for variants when no props are provided.

## Common Patterns

### Button Variants
- Size: sm, md, lg, xl
- Variant: primary, secondary, outline, ghost
- State: default, hover, active, disabled

### Typography Variants
- Size: xs, sm, base, lg, xl, 2xl
- Weight: light, normal, medium, semibold, bold
- Color: primary, secondary, muted, accent

## Benefits

- **Consistency**: Ensures variant naming and behavior is consistent
- **Maintainability**: Easy to update variants across components
- **Type Safety**: Catch variant errors at compile time
- **Autocomplete**: IntelliSense for all variant options
- **Scalability**: Manages complex variant systems effortlessly

## Integration with Other Tools

CVA is commonly used with:
- **tailwind-merge**: Resolve class conflicts
- **clsx**: Conditional class names
- **shadcn/ui**: Component library foundation

## Use Cases

- Design system component libraries
- Reusable UI components
- Button and input variants
- Typography systems
- Card and container variants
- Icon button variations
- Badge and tag systems

## Popular Combination

Many modern component libraries use CVA + clsx + tailwind-merge together for a complete variant management solution with conflict resolution and conditional classes.

## Pricing

Free and open-source under the Apache 2.0 license.