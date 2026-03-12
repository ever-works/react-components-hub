## Overview

Immer is a tiny library that simplifies working with immutable state in JavaScript. It allows you to work with mutable syntax while maintaining immutability, using JavaScript Proxies to track changes and produce immutable updates.

## Features

- **Mutable Syntax**: Write code that looks like mutations
- **Immutable Output**: Produces immutable state updates
- **Proxy-Based**: Uses JavaScript Proxies for change detection
- **TypeScript**: Excellent TypeScript support
- **Small Size**: Only 3KB gzipped
- **Zero Dependencies**: No external dependencies
- **Structural Sharing**: Efficient memory usage
- **Frozen State**: Optional automatic freezing

## Core API

### produce()
The main function that accepts base state and a recipe function:
```javascript
const nextState = produce(baseState, draft => {
  draft.property = newValue
})
```

## Integration

### Redux Toolkit
Built-in - Redux Toolkit uses Immer automatically in createSlice and createReducer.

### Zustand
Available via zustand/middleware/immer middleware.

### React setState
Can be used with useState and useReducer.

## Benefits

- **Simpler Code**: No manual spreading/copying
- **Less Errors**: Harder to make immutability mistakes
- **Better Readability**: Code reads like direct mutations
- **Deep Updates**: Easy nested state updates
- **Type Safety**: Maintains TypeScript types

## Common Patterns

### Deep Updates
```javascript
produce(state, draft => {
  draft.user.address.city = 'New York'
})
```

### Array Operations
```javascript
produce(state, draft => {
  draft.items.push(newItem)
  draft.items[0].checked = true
})
```

### Conditional Updates
```javascript
produce(state, draft => {
  if (condition) {
    draft.value = newValue
  }
})
```

## Performance

Immer is fast enough for most use cases. For extremely performance-critical paths, manual immutable updates may still be faster.

## Browser Support

All modern browsers with Proxy support. ES5 fallback available.

## Pricing

Free and open-source under the MIT license.