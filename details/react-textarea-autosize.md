## Overview

React Textarea Autosize is a lightweight textarea component that automatically adjusts its height as content changes. It's a native React version of the popular jQuery Autosize plugin.

## Features

- **Auto-Resize**: Grows and shrinks with content
- **Tiny Size**: Only 1.3KB minified and gzipped
- **Drop-in Replacement**: Works like standard textarea
- **Min/Max Rows**: Control size boundaries
- **TypeScript**: Type definitions included
- **SSR Compatible**: Works with server-side rendering
- **No Dependencies**: Pure React implementation

## Configuration

### minRows
Minimum number of rows to display (default: current rows attribute)

### maxRows
Maximum number of rows before scrolling

### onHeightChange
Callback when height changes

### cacheMeasurements
Optimization flag for static content

## Behavior

- Automatically expands as user types
- Contracts when content is deleted
- Respects minRows setting
- Adds scrollbar at maxRows
- Handles paste events
- Manages window resize

## Use Cases

- Comment boxes
- Message inputs
- Form text fields
- Note-taking interfaces
- Chat applications
- Feedback forms
- Content editing

## Styling

Accepts all standard textarea props including:
- className
- style
- placeholder
- disabled
- etc.

## Performance

Highly optimized with minimal overhead. Uses ResizeObserver when available for better performance.

## Integration

Simple usage:
```jsx
<TextareaAutosize
  minRows={3}
  maxRows={10}
  placeholder="Type here..."
/>
```

## Browser Support

All modern browsers. IE11 supported with polyfills.

## Pricing

Free and open-source under the MIT license.