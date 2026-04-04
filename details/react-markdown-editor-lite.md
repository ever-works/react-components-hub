## Overview

react-markdown-editor-lite provides a lightweight Markdown editor with split-screen editing and preview. It uses a parser-agnostic design where developers supply their own Markdown rendering library such as markdown-it, marked, or custom implementations.

## Features

- Split-screen editing with live preview
- Parser-agnostic architecture: works with markdown-it, marked, or any custom parser
- Built-in plugins for headers, bold, italic, images, links, and more
- Customizable toolbar
- Full-screen editing mode
- Supports controlled component patterns with `value` and `onChange` props

## Integration

Requires installing both the editor package and a Markdown parser:

```
npm install react-markdown-editor-lite@1.3.4 --save
npm install markdown-it --save
```

The editor accepts a `renderHTML` prop where you pass your parser's render function, along with `value`, `onChange`, `style`, and `plugins` props for configuration.

## Status and Limitations

- No commits in over 2 years
- 58 unresolved issues on GitHub
- Lacks TypeScript definitions
- Uses `!important` CSS rules that create barriers to style overrides
- No server-side rendering support

## Pricing

Free and open-source.