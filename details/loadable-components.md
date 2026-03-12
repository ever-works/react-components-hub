## Overview

Loadable Components (@loadable/component) provides a complete code-splitting solution for React applications with full server-side rendering support, addressing limitations of React.lazy.

## Features

- **SSR Support**: Complete server-side rendering compatibility
- **Code Splitting**: Automatic code splitting
- **Prefetching**: Preload components before rendering
- **Library Splitting**: Split not just components but libraries too
- **Full Dynamic Import**: Support for dynamic import expressions
- **Timeout**: Loading timeout configuration
- **Error Handling**: Comprehensive error boundaries
- **TypeScript**: Full TypeScript support

## Advantages over React.lazy

- Server-side rendering support
- Multiple export handling
- Library code splitting
- Preloading capabilities
- More flexible fallback options
- Better error recovery
- Webpack/Babel plugin integration

## Key Capabilities

### Component Loading
```javascript
const MyComponent = loadable(() => import('./MyComponent'))
```

### Library Loading
```javascript
const Moment = loadable.lib(() => import('moment'))
```

### Prefetching
```javascript
MyComponent.preload()
```

## SSR Configuration

Provides Webpack and Babel plugins for proper SSR setup:
- @loadable/webpack-plugin
- @loadable/babel-plugin
- ChunkExtractorManager
- ChunkExtractor

## Loading States

- Loading fallback components
- Error boundaries
- Timeout handling
- Retry mechanisms

## Use Cases

- Server-rendered React applications
- Next.js alternatives
- Large-scale applications
- Performance optimization
- Route-based code splitting
- Component-based splitting
- Library code splitting

## Performance Benefits

- Reduced initial bundle size
- Faster time to interactive
- Better caching strategies
- Optimized resource loading

## Pricing

Free and open-source under the MIT license.