## Overview

TanStack Router is a modern, fully type-safe routing solution for React that emerged as a leading router in 2025-2026. It evolved from React Location and offers 100% type safety without compromising developer experience.

## Features

- **100% Type-Safe**: Fully typed routes generated at build time
- **Code Splitting**: Automatic code splitting per route
- **Intelligent Preloading**: Smart route preloading
- **Data Loading**: Loader API with caching and preloading
- **Search Params**: Type-safe search parameter handling
- **Nested Routing**: Full nested route support
- **DevTools**: Comprehensive debugging tools
- **Lightweight**: ~12-45KB depending on features used

## Core Concepts

### File-Based Routing
Optional file-based routing with full TypeScript support.

### Route Loaders
Data fetching at the route level:
```javascript
route.createRoute({
  loader: async () => fetchData()
})
```

### Search Params
Type-safe search parameter validation and parsing.

### Pending States
Built-in pending states for navigation and loading.

## Advanced Features

- Route masking (show different URL)
- Route preloading strategies
- Automatic cache invalidation
- Suspense integration
- Error boundaries per route
- Route context
- Before/after load hooks

## Performance

- Automatic code splitting per route
- Intelligent prefetching
- Built-in caching layer
- Optimistic UI updates
- Parallel data loading

## DevTools

Comprehensive devtools showing:
- Current route tree
- Loaded routes
- Cached data
- Search params
- Navigation history

## TypeScript Benefits

- Autocomplete for all routes
- Type-safe route params
- Type-safe search params
- Type-safe route context
- Compile-time route validation

## When to Use

Best for:
- Complex dashboard applications
- Apps with dozens of routes
- Nested layouts
- Complex data relationships
- TypeScript projects prioritizing safety

## vs React Router

TanStack Router is larger (45KB vs 20KB) but provides:
- Full TypeScript integration
- Built-in data loading
- Automatic code splitting
- Integrated caching
- Better devtools

## Pricing

Free and open-source under the MIT license.