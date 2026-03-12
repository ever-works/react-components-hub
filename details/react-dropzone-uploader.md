## Overview

React Dropzone Uploader is a customizable file dropzone and uploader component for React that provides complete upload functionality, unlike react-dropzone which only handles file selection.

## Features

- **File Metadata**: Detailed information for images, videos, and audio
- **Upload Progress**: Real-time progress tracking
- **Upload Control**: Cancel and restart capabilities
- **File Previews**: Preview images, videos, and audio files
- **Drag & Drop**: Intuitive drag-and-drop interface
- **Validation**: File type and size validation
- **Multiple Files**: Support for multiple file uploads
- **Customizable UI**: Fully customizable components

## File Handling

### File Metadata
- File name, size, and type
- Image dimensions and EXIF data
- Video duration and dimensions
- Audio duration and metadata
- Creation and modification dates

### Upload Status
- Preparing: File validation
- Getting upload URL: Requesting upload endpoint
- Uploading: Active upload with progress
- Headers received: Upload processing
- Done: Successfully uploaded
- Error: Upload failed
- Aborted: User cancelled
- Restarted: Retry after failure

## Customization Options

### Layout Components
- Input component
- Preview component
- Submit button component
- Layout component (wrap everything)

### Styling
- Custom CSS classes
- Inline styles
- className props
- Style prop

### Behavior
- Auto-upload on file selection
- Manual upload with submit button
- Max files limit
- Accept file types
- Max file size
- Multiple files toggle

## Upload Methods

- XHR uploads to custom endpoints
- Multipart form data
- Custom headers
- Custom request body
- Progress events
- Abort controller

## Events & Callbacks

- onChangeStatus: File status changes
- onSubmit: Manual upload trigger
- getUploadParams: Get upload URL and params
- validate: Custom file validation

## Validation

- File type restrictions
- File size limits
- Custom validation functions
- Error messaging
- Visual feedback

## Requirements

Requires React 16.2.0 or later.

## Use Cases

- Image upload forms
- Document upload portals
- Media library uploads
- Profile picture uploaders
- Multi-file upload interfaces
- Resume/CV uploads
- Attachment systems

## Pricing

Free and open-source under the MIT license.