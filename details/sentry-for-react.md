## Overview

Sentry for React (@sentry/react) is a comprehensive error tracking and monitoring solution that automatically captures errors, provides detailed context, and helps teams resolve issues faster in production React applications.

## Features

- **Error Boundaries**: Automatic React error boundary integration
- **Source Maps**: Upload source maps for readable stack traces
- **Breadcrumbs**: Track user actions leading to errors
- **Context**: Capture additional context with errors
- **User Feedback**: Collect feedback from users who encounter errors
- **Performance Monitoring**: Track application performance
- **Session Replay**: Watch user sessions leading to errors
- **Release Tracking**: Associate errors with releases

## Error Boundary Component

```javascript
import * as Sentry from '@sentry/react'

<Sentry.ErrorBoundary
  fallback={<ErrorFallback />}
  onError={(error, errorInfo) => {...}}
>
  <App />
</Sentry.ErrorBoundary>
```

## Key Capabilities

### Automatic Capture
- Uncaught exceptions
- Promise rejections
- React component errors
- Network errors
- Console errors

### Context Enrichment
- User information
- Custom tags
- Extra data
- Environment details
- Device information

### React-Specific Features

- Component stack traces (React 17+)
- Component tree in error.cause
- Profiler integration
- React Router integration
- Redux state capture

## Performance Monitoring

- Automatic performance tracking
- Custom transactions
- Component render tracking
- API call monitoring
- Resource timing

## Integration

### React Router
```javascript
import { withSentryRouting } from '@sentry/react'
const SentryRoutes = withSentryRouting(Routes)
```

### Redux
```javascript
import { createReduxEnhancer } from '@sentry/react'
const sentryEnhancer = createReduxEnhancer()
```

## Source Maps

Upload source maps for production error debugging:
- Sentry CLI
- Webpack plugin
- Vite plugin
- Build tool integrations

## User Feedback

Collect user feedback when errors occur:
- Show feedback dialog
- Attach to error events
- Custom feedback forms

## Alerts & Notifications

- Email notifications
- Slack integration
- PagerDuty alerts
- Custom webhooks
- Issue assignment

## Dashboard Features

- Error frequency trends
- Affected users
- Stack trace analysis
- Breadcrumb timeline
- Release comparisons

## Use Cases

- Production error monitoring
- Performance tracking
- User experience monitoring
- Release quality assessment
- Debugging production issues
- Team collaboration on bugs

## Pricing

Free tier available with limited events. Paid plans based on event volume and features.