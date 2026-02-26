## Overview

react-sticky-el creates sticky elements that become fixed when scrolling. When activated, it applies inline styles for fixed positioning while maintaining the original width to prevent layout shifts.

## Features

- Automatic position calculation
- Width preservation
- No layout jumping
- Top and bottom stickiness
- Scroll container support
- Offset configuration
- Boundary elements
- Disable on mobile option
- Performance optimized
- ResizeObserver support
- TypeScript definitions
- Zero dependencies

## Behavior

- Applies `position: fixed` when scrolled
- Maintains original width
- Top or bottom positioning
- Respects scroll boundaries
- Smooth transitions

## Configuration

- mode: 'top' or 'bottom'
- offset: Offset from edge
- onFixedToggle: State change callback
- boundaryElement: Scroll boundary
- scrollElement: Custom scroll container
- disabled: Disable sticky behavior
- stickyStyle: Custom styles when sticky

## Props

- topOffset: Top offset when sticky
- bottomOffset: Bottom offset
- hideOnBoundaryHit: Hide at boundary
- dontUpdateHolderHeightWhenSticky: Performance option

## Use Cases

- Sticky navigation headers
- Fixed sidebars
- Sticky table headers
- Floating action buttons
- Persistent controls
- Sticky footers
- Fixed toolbars

## Pricing

Free and open-source under the MIT license.