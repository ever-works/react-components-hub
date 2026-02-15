## Overview

React Lazyload is a React component for lazy loading images and other content, improving page load performance by deferring loading until content is visible in the viewport.

## Key Features

- **Viewport Detection**: Load when visible
- **Image Lazy Loading**: Optimize images
- **Video Lazy Loading**: Defer video loading
- **Placeholder Support**: Show placeholder
- **Threshold Control**: Custom trigger distance
- **Event Callbacks**: onContentVisible callback
- **Responsive Images**: srcSet support
- **TypeScript**: Type support

## Features

- Intersection Observer API
- Image lazy loading
- Video lazy loading
- Custom placeholders
- Scroll event fallback
- Offset threshold
- Scroll parent support
- Visibility detection
- Callback on visible
- Scroll listening

## Props

- offset: Trigger distance
- height: Fixed height
- once: Load once only
- placeholder: Placeholder component
- onContentVisible: Visibility callback
- debounce: Debounce scroll
- scroll: Enable scroll detection
- scrollContainer: Custom scroll parent

## Usage

```jsx
<LazyLoad height={200} offset={100}>
  <img src="image.jpg" />
</LazyLoad>
```

## Performance Benefits

- Reduced initial load
- Lower bandwidth usage
- Faster page rendering
- Better mobile experience
- Improved Core Web Vitals

## Use Cases

- Image Galleries
- Infinite Scroll Lists
- Heavy Content Pages
- Photo Portfolio
- E-commerce Products
- Blog Images
- Background Images

## Browser Support

- Modern browsers (Intersection Observer)
- IE with polyfill

## Pricing

Free and open-source under the MIT license.