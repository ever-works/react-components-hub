## Overview

React Signature Canvas is a lightweight React wrapper component around signature_pad, providing a simple way to capture signatures using HTML5 canvas. Written in under 150 lines of code with 100% test coverage.

## Features

- Smooth signature drawing
- Customizable pen color and thickness
- Canvas size configuration
- Save signature as data URL (PNG, JPEG, SVG)
- Load existing signatures
- Clear functionality
- Check if canvas is empty
- Velocity-based width variation
- Pressure sensitivity support
- Dot drawing for single taps
- TypeScript support
- Small bundle size
- Mobile and touch device support
- Responsive canvas sizing

## API Methods

- isEmpty(): Check if signature exists
- clear(): Clear the canvas
- toDataURL(type, encoderOptions): Export signature
- fromDataURL(dataURL, options): Load signature
- toData(): Get raw point data
- fromData(pointGroups): Load from point data

## Props

- penColor: Stroke color
- minWidth: Minimum stroke width
- maxWidth: Maximum stroke width
- velocityFilterWeight: Smoothing
- canvasProps: HTML canvas attributes

## Use Cases

- Document signing
- Agreement forms
- Delivery confirmations
- Medical consent forms
- Contract signatures

## Pricing

Free and open-source under the MIT license.