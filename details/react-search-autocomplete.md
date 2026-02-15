## Overview

react-search-autocomplete is a flexible React component that provides search and autocomplete functionality. It leverages Fuse.js for fuzzy search capabilities, allowing users to find results even with partial or misspelled queries.

## Features

- Fuzzy search with Fuse.js v6.5.3
- Fully customizable dropdown
- TypeScript support
- Mobile friendly
- Keyboard navigation
- Search result highlighting
- Custom result rendering
- debounced searching
- Easy integration
- No external UI dependencies

## Props

- items: Array of objects to search
- onSelect: Callback when item is selected
- onSearch: Callback when search term changes
- fuseOptions: Custom Fuse.js search options
- placeholder: Input placeholder text
- styling: Custom CSS classes

## Installation

```bash
npm i react-search-autocomplete
```

## Basic Usage

```jsx
const items = [
  { id: 1, name: 'John' },
  { id: 2, name: 'Jane' }
];

<ReactSearchAutocomplete items={items} onSelect={handleSelect} />
```

## Pricing

Free and open source under the MIT license.