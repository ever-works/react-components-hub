## Overview

Wouter is a minimalist routing library for React and Preact with a hooks-based API. At just ~1.5KB gzipped, it's one of the lightest routing solutions available.

## Features

- **Tiny Size**: Only ~1.5KB gzipped
- **Hook-Based**: Modern hooks API
- **Zero Dependencies**: No external dependencies
- **TypeScript**: Full TypeScript support
- **SSR Compatible**: Works with server-side rendering
- **Familiar API**: Similar to React Router
- **Extensible**: Customizable matching and navigation

## Core Hooks

### useRoute
Match current location:
```javascript
const [match, params] = useRoute('/users/:id')
```

### useLocation
Access and update location:
```javascript
const [location, setLocation] = useLocation()
```

### useParams
Access route parameters:
```javascript
const params = useParams()
```

## Components

### Route
```jsx
<Route path="/about" component={About} />
```

### Link
```jsx
<Link href="/users">Users</Link>
```

### Switch
```jsx
<Switch>
  <Route path="/" component={Home} />
  <Route path="/about" component={About} />
</Switch>
```

## Advanced Features

- Nested routes
- Route parameters
- Query strings (with external library)
- Custom matcher
- Base path support
- Hash routing
- Memory routing for testing

## Customization

- Custom location hook
- Custom matcher function
- Custom path parser
- Custom navigation logic

## Use Cases

- Small to medium applications
- Projects prioritizing bundle size
- Simple routing needs
- Preact applications
- Microservices/microfrontends

## Performance

Minimal overhead with no complex routing logic. Perfect for performance-critical applications.

## Comparison

- **vs React Router**: Much smaller, simpler API
- **vs TanStack Router**: Less features but much lighter
- **vs Reach Router**: More modern with hooks

## Pricing

Free and open-source under the MIT license.