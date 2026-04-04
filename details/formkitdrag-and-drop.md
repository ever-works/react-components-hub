## Overview

formkit/drag-and-drop is a drag-and-drop library developed by the team behind FormKit. Unlike traditional DnD libraries that manipulate the DOM directly, it updates an underlying reactive data model that you provide, making it feel like a natural extension of reactive frameworks like React and Vue.

It is framework-agnostic and ships with thin wrappers for React and Vue. The library is currently pre-1.0 (around version 0.3) but is gaining traction for its minimal, intuitive approach.

## Features

- **Lightweight** — approximately 5KB gzipped, one of the smallest DnD libraries available
- **Plugin system** — built-in plugins for customizing item previews, modifying drop selection behavior, and adding animations without bloating the core
- **Reactive data model** — updates your data structure instead of directly manipulating the DOM, allowing natural integration with React state
- **React hook API** — simple setup using a hook that connects directly to your data model, providing a state-driven way to render items along with a ref for the parent drop container
- **Framework agnostic** — works with any JavaScript framework; official thin wrappers for React and Vue
- **Declarative API** — minimal boilerplate, React-friendly approach to drag-and-drop

## Limitations

- Documentation is minimal with fewer examples for complex use cases
- Small and niche community; currently pre-1.0 release
- Limited accessibility: basic screen reader support but lacks proper keyboard navigation and has inconsistencies on mobile
- API is subject to change as the library evolves

## Best Use Cases

- Simple drag-and-drop functionality like moving items between containers or reordering lists
- Projects where bundle size is a priority
- Applications that benefit from a declarative, state-driven DnD approach
- Not ideal for complex interactions required in design tools or highly customized layouts

## Pricing

Free and open-source.