## Overview

react-contexify is a lightweight React library for adding context menus to your application. It provides a simple API for creating customizable context menus that appear on right-click or programmatic triggers.

## Features

- Simple and intuitive API
- Customizable menu items and separators
- Support for icons and custom content
- Keyboard navigation support
- Touch screen support
- Portal rendering for proper z-index handling
- Animation support
- TypeScript support
- Accessibility attributes
- No external dependencies

## Components Included

- ContextMenu (wrapper component)
- Item (menu item)
- Separator (divider)
- Submenu (nested menus)
- Loader (loading state)

## Usage Example

```jsx
import { ContextMenu, Item } from 'react-contexify';

<ContextMenu id="menu_id">
  <Item onClick={handleSave}>Save</Item>
  <Item onClick={handleDelete}>Delete</Item>
</ContextMenu>
```

## Pricing

Free and open source under the MIT license.