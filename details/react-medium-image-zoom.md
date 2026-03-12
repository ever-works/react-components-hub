## Overview

React Medium Image Zoom provides a Medium.com-style image zoom effect for React applications. It's lightweight, accessible, and easy to implement.

## Features

- **Medium-Style Zoom**: Smooth zoom animation like Medium.com
- **Accessibility**: Keyboard and screen reader support
- **Touch Support**: Mobile-friendly interactions
- **Controlled/Uncontrolled**: Both modes supported
- **Custom Triggers**: Zoom on click, hover, or custom event
- **Portal Support**: Render zoomed image in portal
- **No Dependencies**: Minimal external dependencies
- **TypeScript**: Full TypeScript support

## Zoom Behavior

- Click to zoom in
- Click or ESC to zoom out
- Background overlay
- Smooth scale animation
- Image centering
- Scroll lock when zoomed

## Configuration Options

- Custom zoom margin
- Custom overlay background
- Portal target customization
- Zoom modal class names
- Scroll offset
- Transition duration
- Close on click outside

## Accessibility

- Keyboard navigation (ESC to close)
- ARIA attributes
- Focus management
- Screen reader announcements
- Semantic HTML

## Use Cases

- Blog post images
- Product detail pages
- Documentation screenshots
- Portfolio images
- Article illustrations
- Technical documentation

## Integration

Simple wrapper component - just wrap your image:
```jsx
<Zoom>
  <img src="image.jpg" alt="description" />
</Zoom>
```

## Performance

Lightweight with minimal performance impact. Uses CSS transforms for smooth animations.

## Pricing

Free and open-source under the MIT license.