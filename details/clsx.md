## Overview

clsx is a lightweight utility library for conditionally joining className strings together. It's faster and smaller than the classnames library and has become the de facto standard for managing dynamic classes in React applications.

## Features

- **Tiny**: Less than 1KB minified and gzipped
- **Fast**: Optimized for performance
- **Flexible**: Accepts strings, objects, arrays, and mixed types
- **Type-Safe**: Full TypeScript support
- **Zero Dependencies**: No external dependencies
- **Framework Agnostic**: Works with any JavaScript framework

## Input Types Supported

- Strings: Direct class names
- Objects: Conditional classes based on boolean values
- Arrays: Multiple class names or conditions
- Mixed: Combination of all types
- Falsy Values: Automatically filtered out

## Common Patterns

### Object Syntax
```javascript
clsx({ active: isActive, disabled: isDisabled })
```

### Array Syntax
```javascript
clsx(['btn', isLarge && 'btn-large'])
```

### Mixed Syntax
```javascript
clsx('btn', { active: isActive }, [isLarge && 'btn-large'])
```

## Use Cases

- Conditional styling in React components
- Dynamic class name generation
- CSS Modules integration
- Tailwind CSS class management
- Component variant systems
- Theme switching
- Responsive class handling

## Performance

clsx is significantly faster than the classnames library and uses less memory, making it ideal for performance-critical applications.

## Integration

Often used in combination with tailwind-merge to create the popular `cn()` utility function seen in shadcn/ui and other modern React component libraries.

## Pricing

Free and open-source under the MIT license.