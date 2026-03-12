## Overview

TanStack Query DevTools is a set of developer tools designed to help you visualize and debug TanStack Query (formerly React Query) cache states, queries, and mutations in real-time.

## Features

- **Cache Visualization**: View all cached queries
- **Query Details**: Inspect query state, data, and metadata
- **Mutation Tracking**: Monitor ongoing mutations
- **Real-Time Updates**: Live cache state updates
- **Time Travel**: View query state over time
- **Manual Refetch**: Trigger query refetch from devtools
- **Cache Invalidation**: Invalidate queries manually
- **Multiple Modes**: Floating panel or embedded mode

## Installation

```bash
npm install @tanstack/react-query-devtools
```

## Usage

### Basic Setup
```jsx
import { ReactQueryDevtools } from '@tanstack/react-query-devtools'

function App() {
  return (
    <QueryClientProvider client={queryClient}>
      <App />
      <ReactQueryDevtools initialIsOpen={false} />
    </ReactQueryDevtools>
  )
}
```

## Configuration Options

- **initialIsOpen**: Start with panel open/closed
- **position**: Panel position (bottom-left, bottom-right, top-left, top-right)
- **panelPosition**: Embedded panel position
- **buttonPosition**: Toggle button position
- **styleNonce**: CSP nonce for styles

## Features Detailed

### Query Explorer
- List of all queries
- Query status indicators
- Data preview
- Error inspection
- Observer count

### Query Details
- Query key
- Query state (fresh, fetching, stale, inactive)
- Data and error
- Last updated timestamp
- Cache time remaining
- Stale time remaining

### Actions
- Refetch query
- Invalidate query
- Reset query
- Remove query from cache
- Force error state

## Production Build

DevTools are automatically excluded from production builds when using the standard import.

## TanStack Devtools Panel

New unified devtools panel supporting multiple TanStack libraries (Query, Router, etc.) in one interface.

## Use Cases

- Debugging data fetching issues
- Understanding cache behavior
- Optimizing query configuration
- Teaching/learning React Query
- Monitoring query performance
- Testing cache invalidation logic

## Version

Latest version: 5.91.3 (as of 2026)

## npm Stats

492+ packages depend on TanStack Query DevTools

## Pricing

Free and open-source under the MIT license.