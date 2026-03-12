## Overview

Valtio is a minimal, proxy-based state management library that makes state mutation direct and simple. It's especially praised for its straightforward design, making it accessible to beginners and refreshing for experienced developers.

## Features

- **Proxy-Based**: Mutate state directly using proxies
- **Minimal API**: Simple and intuitive interface
- **Auto-Tracking**: Automatic dependency tracking
- **React Integration**: useSnapshot hook for components
- **TypeScript**: Full TypeScript support
- **Vanilla JS**: Can be used outside React
- **DevTools**: Redux DevTools support
- **SSR Compatible**: Works with Next.js

## Core API

### proxy()
Create a proxy state:
```javascript
import { proxy } from 'valtio'
const state = proxy({ count: 0, text: 'hello' })
```

### useSnapshot()
Use state in React components:
```javascript
import { useSnapshot } from 'valtio'
const snap = useSnapshot(state)
```

### Mutation
Direct mutation:
```javascript
state.count++
state.text = 'world'
```

## Advanced Features

### Nested Objects
Proxy works recursively:
```javascript
state.nested.deep.value = 10
```

### Arrays
Array mutations work naturally:
```javascript
state.items.push(newItem)
state.items[0].checked = true
```

### Computed Values
Derive values with subscribe:
```javascript
const derived = derive({
  doubled: (get) => get(state).count * 2
})
```

## Utilities

- **subscribe**: Listen to state changes
- **snapshot**: Get immutable snapshot
- **ref**: Mark values as non-reactive
- **derive**: Create derived state
- **devtools**: Redux DevTools integration

## Use Cases

- Applications preferring mutable syntax
- Migrating from MobX
- Prototypes and MVPs
- Simple global state
- Form state management
- UI state

## Performance

Efficient automatic dependency tracking ensures only affected components re-render. Minimal overhead from proxy.

## Integration with Jotai

Valtio can be integrated with Jotai through Jotai's Valtio extension.

## Comparison

- **vs Zustand**: More mutable, less boilerplate
- **vs MobX**: Lighter, simpler API
- **vs Redux**: Much less boilerplate

## Best For

Beginners and developers who prefer straightforward, mutable state management without complex abstractions.

## Pricing

Free and open-source under the MIT license.