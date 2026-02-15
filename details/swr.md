## Overview

SWR (Stale-While-Revalidate) is a React hooks library for data fetching that provides a simpler alternative to React Query with built-in caching and revalidation strategies.

## Key Features

- **Stale-While-Revalidate**: Cache-first strategy
- **Real-time**: Auto-revalidate on focus
- **Smart Caching**: Automatic cache management
- **Lightweight**: Minimal bundle size
- **Suspense Support**: React Suspense compatible
- **TypeScript**: Full type support
- **Global Configuration**: App-wide settings
- **Middleware**: Custom data transformations

## Features

- Data fetching hook (useSWR)
- Automatic revalidation
- Focus tracking
- Interval polling
- Offline support
- Error retry
- Dedupe requests
- Local mutation
- Conditional fetching
- Dependent requests

## Configuration

- revalidateOnFocus: Revalidate on window focus
- revalidateOnReconnect: Revalidate on reconnect
- revalidateIfStale: Revalidate if stale
- shouldRetryOnError: Auto-retry on error
- dedupingInterval: Dedup window
- focusThrottleInterval: Focus throttle
- errorRetryCount: Retry count
- errorRetryInterval: Retry interval

## Hook API

```jsx
const { data, error, isLoading } = useSWR('/api/user', fetcher)
```

## Use Cases

- API Data Fetching
- Real-time Updates
- Caching Data
- Offline Support
- Auto-revalidation
- Polling
- Dependent Queries

## Benefits

- Simpler API
- Better UX
- Lighter weight
- Great defaults
- Vercel integration

## Pricing

Free and open-source under the MIT license.