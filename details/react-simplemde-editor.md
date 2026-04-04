## Overview

react-simplemde-editor is a React wrapper for EasyMDE, which itself is a maintained fork of the original SimpleMDE Markdown editor. It provides Markdown editing with live preview, toolbar customization, and autosaving functionality through React-friendly props.

## Features

- Markdown editing with live preview
- Full EasyMDE configuration exposed via the `options` prop
- Toolbar customization (bold, italic, heading, preview, and more)
- Autosave functionality
- Spell checker configuration
- Preview rendering options

## Integration

Requires both the wrapper package and EasyMDE as a peer dependency:

```
npm install --save react-simplemde-editor@5.2.0 easymde
```

The component accepts `value`, `onChange`, and `options` props for configuration. The `options` prop supports full EasyMDE configuration including toolbar customization, autosave settings, spell checker, and preview rendering.

## Status and Limitations

- No active maintenance for over 3 years
- Partial TypeScript support: lacks dedicated `.d.ts` type definition files
- React ref problems with function components
- Known mobile browser compatibility bugs
- Not recommended for new production projects

## Pricing

Free and open-source.