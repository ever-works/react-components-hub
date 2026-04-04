## Overview

AutoAnimate is a zero-configuration animation library that automatically adds smooth layout transitions to your app with zero config.

## Features

- Zero configuration — just add a single hook
- Automatically detects DOM changes and applies animations
- Supports conditional rendering and list reordering
- Only 1.5 KB gzipped
- Customizable durations and easing curves
- Works with any React component
- Can be disabled/enabled dynamically

## Usage

```js
const [parent] = useAutoAnimate()
return <ul ref={parent}>{items.map(...)}</ul>
```

## Pricing

Free and open-source under the MIT license.