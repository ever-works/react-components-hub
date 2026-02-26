## Overview

React Avatar Editor is a specialized component for creating avatar and profile pictures. It provides an intuitive interface for users to resize, crop, and rotate images with customizable borders and scaling.

## Features

- Image cropping
- Image scaling/zoom
- Image rotation
- Drag to position
- Circular or square crops
- Border customization
- Border radius control
- Custom border color
- High-quality output
- Export to canvas
- Export to data URL
- Export to blob
- Touch device support
- Mouse wheel zoom
- TypeScript support

## Configuration

- width, height: Editor dimensions
- border: Border size (array or number)
- borderRadius: Corner radius or circle
- color: Border/background color
- scale: Zoom level (1-infinity)
- rotate: Rotation angle (0-360)
- position: Image position {x, y}

## Export Options

- getImage(): Canvas element
- getImageScaledToCanvas(): Scaled canvas
- getCroppingRect(): Crop coordinates

## Output Formats

- PNG with transparency
- JPEG
- Base64 data URL
- Blob for upload

## Use Cases

- Profile picture upload
- Avatar creation
- User registration
- Social media profiles
- Team member photos
- Contact management
- ID badge creation

## Pricing

Free and open-source under the MIT license.