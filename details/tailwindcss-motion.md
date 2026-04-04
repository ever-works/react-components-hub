## Overview

TailwindCSS Motion is a Tailwind CSS plugin that enables lightweight, pure CSS animations through utility classes and presets. It eliminates the need for heavy JavaScript animation libraries when simple UI transitions are sufficient, making it ideal for Tailwind-based React projects.

## Features

- **Zero JavaScript overhead**: Pure CSS animations compiled at build time with no runtime cost
- **Preset animations**: Built-in presets including `motion-preset-fade`, `motion-preset-slide-up`, `motion-preset-slide-up-lg`, `motion-preset-bounce`, and more
- **Composable utilities**: Granular utilities like `motion-translate-x-in-25`, `motion-opacity-in-0`, `motion-rotate-in-90`, and `motion-scale-in-50` for custom animation composition
- **Duration control**: Classes like `motion-duration-700` to set animation timing
- **Visual animator**: Rombo Chrome Extension for creating animations visually and exporting them as Tailwind classes
- **TypeScript support**: Full type definitions out of the box for theme customizations and plugin configuration
- **Lightweight**: Approximately 5KB gzipped, adding minimal overhead to CSS bundles
- **Seamless Tailwind integration**: Works natively with existing utility-first workflows

## Installation

```bash
npm i -D tailwindcss-motion
```

Add to your `tailwind.config.js`:

```js
// CommonJS
export default {
  content: [...],
  theme: { extend: {...} },
  plugins: [require('tailwindcss-motion')],
};

// ESM
import tailwindcssMotion from "tailwindcss-motion";
export default {
  content: [...],
  theme: { extend: {} },
  plugins: [tailwindcssMotion],
};
```

## Usage

Animations are triggered using Tailwind utility classes:

```jsx
className={`bg-white p-8 rounded-lg shadow-lg ${
  isVisible[index]
    ? "motion-preset-slide-up-lg motion-duration-700"
    : "opacity-0 translate-y-12"
}`}
style={{ transitionDelay: `${index * 150}ms` }}
```

Stagger effects can be achieved with inline `transitionDelay` styles.

## Pros

- Pure CSS means no additional runtime cost
- Integrates seamlessly with Tailwind's utility-first workflow
- Extremely lightweight at ~5KB gzipped
- Full TypeScript support
- Composable granular utilities for custom animations
- Visual animator via Chrome Extension

## Cons

- Requires Tailwind CSS — not suitable for non-Tailwind codebases
- Limited dynamic control — CSS-based animations cannot handle complex interactive animations requiring JavaScript state
- Smaller community compared to established libraries like Motion or GSAP

## Performance

In benchmark testing, Tailwind CSS Motion achieved approximately 5KB gzipped bundle size and excellent scroll performance (5/5 stars). Implementation required 128 lines of code and received a developer experience score of 9/10.

## Pricing

Free and open-source under the MIT license.