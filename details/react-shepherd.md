## Overview

React Shepherd is a React wrapper for Shepherd.js, a mature tour library that works across frameworks. It uses Popper.js to render responsive overlay dialogs and can be integrated into applications quickly with minimal code.

## Features

- Step-by-step guided tours
- Popper.js positioning
- Responsive dialogs
- Keyboard navigation
- Custom step content
- Arrow attachments
- Modal overlays
- Step buttons customization
- Sequential navigation
- Tour hooks (useShepherd)
- Theme customization
- Arrow styling
- Cancel/complete callbacks
- Scroll to elements
- TypeScript support

## Components

- ShepherdTour: Tour provider
- TourMethods: Hook for tour control
- Step definitions
- Button configurations

## Step Configuration

- id: Unique step identifier
- text: Step content
- attachTo: Target element + position
- buttons: Navigation buttons
- classes: Custom CSS classes
- scrollTo: Auto-scroll behavior

## Tour Control

- start(): Begin tour
- next(): Next step
- back(): Previous step
- complete(): Finish tour
- cancel(): Exit tour

## Use Cases

- Feature introductions
- User onboarding
- Product walkthroughs
- Interactive help systems
- Tutorial creation
- New feature announcements

## Pricing

Free and open-source under the MIT license. Note: Shepherd.js uses AGPL license which requires commercial license for commercial use.