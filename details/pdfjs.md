## Overview

PDF.js is a JavaScript library for parsing and rendering PDF files, built by Mozilla. It's the engine behind Firefox's PDF viewer and can be integrated into React applications for custom PDF viewing experiences.

## Core Features

- Parse PDF files
- Render PDF pages
- Text extraction
- Metadata extraction
- Page rendering to canvas
- SVG rendering
- Web Worker support
- Stream processing
- Incremental loading
- Password-protected PDFs

## Rendering Capabilities

- Canvas-based rendering
- SVG-based rendering
- Text layer rendering
- Annotation layer rendering
- XFA form rendering
- High-quality scaling
- Custom DPI
- Rotation support

## API Features

- getDocument() - load PDF
- getPage() - get specific page
- render() - render to canvas
- getTextContent() - extract text
- getMetadata() - PDF metadata
- getOutline() - document outline
- getAnnotations() - page annotations
- getOperatorList() - drawing operations

## Performance

- Web Worker for parsing (non-blocking)
- Streaming support
- Lazy loading
- Caching
- Memory management
- Progressive rendering

## Advanced Features

- Search functionality
- Find controller
- Thumbnail generation
- Print support
- Download support
- Annotation rendering
- Form field support
- Signature display
- Attachment extraction

## React Integration

- Use directly with React
- Or use react-pdf wrapper
- Manual canvas integration
- Hooks-based implementation
- State management

## Security

- Sandbox environment
- Safe rendering
- XSS protection
- Content Security Policy compatible

## Browser Support

- All modern browsers
- IE11 with polyfills
- Mobile browsers
- Safari iOS
- Chrome Android

## Customization

- Custom rendering pipeline
- Text layer styling
- Canvas manipulation
- Custom fonts
- Custom CMaps

## Use Cases

- PDF viewers
- Document management systems
- E-learning platforms
- Digital publishing
- Form filling applications
- Invoice systems

## File Format Support

- PDF 1.0 through 2.0
- Encrypted PDFs
- Tagged PDFs
- PDF/A
- Linearized PDFs
- XFA forms (limited)

## Pricing

Free and open-source under the Apache 2.0 license.