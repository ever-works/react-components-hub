## Overview

Reapop is a React notification library that provides both state management primitives and UI display capabilities for toast notifications. Unlike libraries that only handle toast display, Reapop provides Redux-compatible notification management, making it ideal for applications already using Redux that want consistent state management patterns.

## Features

- Redux integration with actions and reducers for centralized notification state
- Centralized notification state management across the application
- Theme support with customizable styling
- Notification positioning and timing controls
- TypeScript support
- NotificationsProvider component for context-based notification management
- Integration with React Redux via useReducer

## Quick Example

```tsx
import { NotificationsProvider, notify } from 'reapop';
import { useDispatch } from 'react-redux';

function App() {
  const dispatch = useDispatch();
  const showNotification = () => {
    dispatch(notify({
      title: 'Success',
      message: 'Operation completed successfully!',
      status: 'success',
    }));
  };

  return (
    <NotificationsProvider>
      <button onClick={showNotification}>Show Notification</button>
    </NotificationsProvider>
  );
}
```

## Pricing

Free and open-source.