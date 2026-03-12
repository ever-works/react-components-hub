## Overview

Jotai is a primitive and flexible state management library for React that takes a bottom-up approach using an atomic model inspired by Recoil. It's particularly effective for applications requiring fine-grained control over state.

## Features

- **Atomic Model**: State as atoms (pieces of state)
- **Bottom-Up Approach**: Build complex state from simple atoms
- **TypeScript**: First-class TypeScript support
- **Minimal Boilerplate**: Simple API with minimal setup
- **React Suspense**: Built-in Suspense support
- **DevTools**: Redux DevTools integration
- **SSR Compatible**: Works with Next.js and SSR
- **No Provider Hell**: No nested providers needed

## Core Concepts

### Atoms
Primitive units of state:
```javascript
const countAtom = atom(0)
const userAtom = atom({ name: 'John' })
```

### Derived Atoms
Computed values from other atoms:
```javascript
const doubleAtom = atom((get) => get(countAtom) * 2)
```

### Writable Derived Atoms
Atoms with custom write logic:
```javascript
const atomWithWrite = atom(
  (get) => get(baseAtom),
  (get, set, newValue) => set(baseAtom, newValue)
)
```

## Integrations

### Extensions Available
- **XState**: atomWithMachine for state machines
- **Valtio**: Proxy interface integration
- **Immer**: atomWithImmer for mutable updates
- **Query**: Async data fetching
- **Location**: URL state sync
- **Storage**: Persist to localStorage

## Async Support

Native async atom support with Suspense:
```javascript
const dataAtom = atom(async () => {
  const response = await fetch('/api/data')
  return response.json()
})
```

## Use Cases

- Applications with complex derived state
- Fine-grained reactivity requirements
- Form state management
- Global app state
- Async data management
- Server state caching

## Performance

Excellent performance with automatic dependency tracking and minimal re-renders. Only components using affected atoms re-render.

## Comparison

- **vs Zustand**: More atomic, better for derived state
- **vs Redux**: Less boilerplate, more flexible
- **vs Recoil**: Similar but lighter, better maintained

## Community

~2M weekly npm downloads with active community and regular updates.

## Pricing

Free and open-source under the MIT license.