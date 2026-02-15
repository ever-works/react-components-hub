## Overview

React Cropper is a React component for cropping images with support for touch gestures, customizable aspect ratios, and various output options.

## Key Features

- **Touch Support**: Pinch zoom, drag
- **Aspect Ratio**: Fixed or free aspect
- **Grid Lines**: Visual guides
- **Preview**: Real-time preview
- **Keyboard Support**: Arrow key controls
- **Zoom**: Mouse wheel zoom
- **Rotate**: Image rotation
- **Flip**: Horizontal/vertical flip
- **Export**: Canvas or image output
- **TypeScript**: Type support

## Features

- Image selection
- Crop area selection
- Aspect ratio locking
- Grid overlay
- Zoom controls
- Rotation controls
- Flip controls
- Reset button
- Canvas export
- Data URL export

## Configuration

- src: Image source
- aspectRatio: Crop ratio (free if omitted)
- guides: Show grid lines
- grid: Show grid
- responsive: Responsive sizing
- autoCropArea: Auto crop area
- restrictSize: Min size
- modal: Show modal overlay
- highlight: Highlight crop area

## Methods

- crop(): Get crop data
- setData(): Set crop data
- setImage(): Set new image
- reset(): Reset crop
- rotate(): Rotate image
- scaleX(): Flip horizontally
- scaleY(): Flip vertically
- zoom(): Zoom in/out

## Use Cases

- Avatar Upload
- Product Photos
- Profile Pictures
- Image Editor
- Thumbnail Creation
- Document Scanning

## Output

- Canvas context
- Image data
- Crop coordinates
- Transformed image

## Pricing

Free and open-source under the MIT license.