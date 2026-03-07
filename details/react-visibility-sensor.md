## Overview

React Visibility Sensor is a component that tracks whether an element is visible in the viewport. It's useful for lazy loading, analytics, and triggering animations when elements become visible.

## Features

- Element visibility detection
- Viewport entry/exit callbacks
- Partial visibility support
- Intersection ratio
- Offset configuration
- Interval checking
- Once mode (trigger once)
- Children as function
- Render optimization
- TypeScript support
- Lightweight

## Configuration

- onChange - visibility change callback
- active - enable/disable sensor
- partialVisibility - detect partial visibility
- offset - viewport offset
- intervalCheck - check interval
- intervalDelay - check delay
- scrollCheck - check on scroll
- scrollDelay - scroll check delay
- scrollThrottle - throttle scroll
- resizeCheck - check on resize
- resizeDelay - resize check delay
- containment - custom container
- delayedCall - delayed callback
- minTopValue - minimum top value

## Use Cases

### Lazy Loading
- Images
- Videos
- Components
- Third-party widgets
- Heavy content

### Analytics
- Viewability tracking
- Ad impressions
- Content engagement
- Scroll depth
- Element exposure

### Animations
- Fade-in effects
- Slide-in animations
- Count-up animations
- Progressive reveals
- Stagger animations

### Performance
- Load on demand
- Defer non-critical content
- Reduce initial load
- Optimize resources

## Partial Visibility

- Top visible
- Bottom visible
- Left visible
- Right visible
- Custom thresholds

## Container Detection

- Window viewport
- Custom container
- Scrollable parent
- Overflow containers

## Optimization

- Throttled checks
- Debounced callbacks
- Passive listeners
- Efficient calculations

## Alternative

**Note:** For new projects, consider react-intersection-observer which uses the native Intersection Observer API for better performance.

## Integration

- Animation libraries
- Image lazy loading
- Infinite scroll
- Analytics platforms
- A/B testing

## Pricing

Free and open-source under the MIT license.