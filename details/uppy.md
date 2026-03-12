## Overview

Uppy is a sleek, modular file uploader for web browsers and Node.js. Developed by Transloadit, it's framework-agnostic but provides excellent React integration with hooks and components.

## Features

- **Modular Design**: Pick and choose only the plugins you need
- **Framework Agnostic**: Works with React, Vue, Angular, or vanilla JS
- **Multiple Sources**: Upload from local disk, remote URLs, Google Drive, Dropbox, Instagram, webcam, and more
- **Drag & Drop**: Intuitive drag-and-drop interface
- **Progress Tracking**: Real-time upload progress
- **Resume Uploads**: Continue uploads after interruption
- **File Validation**: Size, type, and custom validation
- **Image Editing**: Crop and edit images before upload

## Core Plugins

### UI Plugins
- Dashboard: Full-featured upload UI
- Drag & Drop: Simple drop zone
- File Input: Traditional file input
- Progress Bar: Minimal progress display
- Status Bar: Upload status information

### Source Plugins
- Webcam: Capture photos/videos
- Screen Capture: Record screen
- Google Drive: Import from Google Drive
- Dropbox: Import from Dropbox
- Instagram: Import from Instagram
- URL: Import from URL

### Processing Plugins
- Image Editor: Crop and rotate images
- Compressor: Compress images
- Audio: Record audio

## Upload Destinations

- Tus (resumable uploads)
- XHR Upload
- AWS S3
- Google Cloud Storage
- Transloadit (encoding service)

## React Integration

Official React components and hooks:
- `@uppy/react` package
- Dashboard component
- DragDrop component
- ProgressBar component
- useUppy hook

## Advanced Features

- Resumable uploads with Tus protocol
- Golden Retriever (restore files and continue on browser crash)
- Thumbnails generation
- Multiple upload providers
- Localization support (30+ languages)
- Customizable UI and styling
- Comprehensive event system

## File Restrictions

- Max file size limits
- Allowed file types
- Max number of files
- Min number of files
- Required meta fields

## Use Cases

- Media upload platforms
- Social media applications
- Document management systems
- E-commerce product uploads
- Profile picture uploaders
- File sharing services
- Content management systems

## Browser Support

Supports all modern browsers (Chrome, Firefox, Safari, Edge) and provides graceful degradation for older browsers.

## Pricing

Free and open-source under the MIT license. Transloadit encoding service available separately.