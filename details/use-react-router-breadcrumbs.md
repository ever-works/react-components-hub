## Overview

A React hook for generating breadcrumbs for React Router 5 and 6. Provides a simple way to create dynamic breadcrumb navigation that automatically syncs with your routing structure.

## Features

- Automatic breadcrumb generation from routes
- Custom breadcrumb names per route
- Dynamic route parameter support
- Component or string breadcrumbs
- Exclude specific routes
- Match object injection
- Location object access
- TypeScript support
- Small bundle size
- Works with nested routes
- Customizable separators
- Active route highlighting
- Skip breadcrumb logic

## API

- useBreadcrumbs(routes, options): Main hook
- routes: Array of route configurations
- options.excludePaths: Paths to exclude
- options.disableDefaults: Disable default breadcrumbs

## Breadcrumb Configuration

- path: Route path
- breadcrumb: String or React component
- props: Match and location objects

## Use Cases

- Multi-level navigation
- Admin dashboards
- E-commerce product categories
- Documentation sites
- File browser interfaces
- Settings pages

## Pricing

Free and open-source under the MIT license.