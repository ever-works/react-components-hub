## Overview

React Error Boundary is a higher-order component and hook-based utility for implementing error boundaries in React, catching errors and displaying fallback UI.

## Key Features

- **Error Catching**: Catch React errors
- **Fallback UI**: Show custom fallback
- **Error Logging**: Log errors
- **Reset Functionality**: Reset error state
- **Hooks Support**: useErrorHandler hook
- **TypeScript**: Type support
- **Custom Rendering**: Render custom UI
- **Multiple Boundaries**: Nested boundaries

## Features

- Catch component errors
- Display error UI
- Error reset button
- Error logging
- Detailed error display
- Isolation of failures
- Child fallback UI
- Error recovery
- Stack trace display

## Components

- **ErrorBoundary**: Wrapper component
- **useErrorHandler**: Hook version

## Props

- FallbackComponent: Fallback UI component
- fallback: Fallback render function
- onError: Error callback
- onReset: Reset callback
- resetKeys: Reset trigger keys
- resetOnPropsChange: Reset on prop change

## Usage

```jsx
<ErrorBoundary FallbackComponent={ErrorFallback}>
  <ComponentThatMayError />
</ErrorBoundary>
```

## Use Cases

- Component Error Handling
- Graceful Degradation
- User Error Messages
- Error Logging
- Error Recovery
- Isolated Failures
- User Experience

## Integration

- Error logging services
- Sentry integration
- Custom logging
- Error tracking

## Pricing

Free and open-source under the MIT license.