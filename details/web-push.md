## Overview

Web Push is a Node.js library that enables server-side push notification delivery using the web push protocol. It's essential for Progressive Web Apps (PWAs) and applications that need to send notifications to users even when the application isn't actively open in the browser.

## Features

- Server-side push notification delivery
- VAPID key support for secure identification
- Cross-browser compatibility
- No third-party dependencies
- Full control over notification infrastructure
- Support for subscription-based push delivery

## Installation

```bash
npm install web-push
```

## Quick Example

```js
const webpush = require('web-push');

webpush.setVapidDetails(
  'mailto:your-email@example.com',
  process.env.VAPID_PUBLIC_KEY,
  process.env.VAPID_PRIVATE_KEY,
);

// Send notification
webpush.sendNotification(
  subscription,
  JSON.stringify({
    title: 'New Message',
    body: 'You have a new notification',
    icon: '/icon.png',
  }),
);
```

## Pricing

Free and open-source.