## Overview

Socket.IO Client enables bi-directional real-time communication between React applications and servers, making it ideal for building live notification systems, chat applications, and collaborative features. It handles WebSocket connections with automatic fallback and reconnection logic.

## Features

- Real-time bi-directional communication between client and server
- Automatic fallback to long polling when WebSocket is unavailable
- Room and namespace support for organized communication
- Built-in error handling and automatic reconnection
- Cross-browser compatibility
- Easy integration with React hooks (useEffect, useState)

## Quick Example

```tsx
import { useEffect, useState } from 'react';
import { io } from 'socket.io-client';

function NotificationComponent() {
  const [notifications, setNotifications] = useState([]);

  useEffect(() => {
    const socket = io('http://localhost:3001');

    socket.on('notification', (data) => {
      setNotifications((prev) => [...prev, data]);
    });

    return () => socket.disconnect();
  }, []);

  return (
    <div>
      {notifications.map((notification) => (
        <div key={notification.id}>{notification.message}</div>
      ))}
    </div>
  );
}
```

## Pricing

Free and open-source.