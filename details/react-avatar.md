## Overview

React Avatar provides a universal avatar component with automatic fallbacks. It can display user images, initials, icons, or custom content, with built-in error handling and styling options.

## Features

- Multiple avatar sources
- Automatic fallbacks
- Initials generation
- Gravatar support
- Facebook graph support
- Google support
- Skype support
- Custom colors
- Various shapes (circle, square, rounded)
- Size configuration
- Text sizing
- Icon fallback
- Error handling
- TypeScript support

## Avatar Sources

1. Image URL (src)
2. Gravatar (email)
3. Facebook (facebookId)
4. Google (googleId)
5. Skype (skypeId)
6. Twitter (twitter)
7. Instagram (instagram)
8. Name initials
9. Value/text
10. Icon fallback

## Source Priority

- Tries sources in order
- Automatic fallback
- Error handling
- Missing image handling
- Network error recovery

## Initials Generation

- From name prop
- First/last initials
- Single letter
- Two letters
- Custom max initials
- Color based on name

## Shapes

- Circle (default)
- Square
- Rounded square
- Custom border radius

## Colors

- Automatic color from name
- Custom background color
- Custom text color
- Predefined color palette
- Consistent color per user

## Sizing

- size prop (px or string)
- Responsive sizing
- Text scaling
- Icon scaling
- Consistent proportions

## Configuration

- src - image URL
- name - for initials
- email - for Gravatar
- size - avatar size
- round - circular shape
- color - background color
- fgColor - foreground color
- textSizeRatio - text size ratio
- maxInitials - max initials
- alt - alt text
- onClick - click handler

## Gravatar

- Email-based avatars
- Automatic fallback
- Default image options
- Rating filter
- Force default option

## Use Cases

### User Interfaces
- Profile pictures
- Comment avatars
- Team member lists
- User mentions
- Chat interfaces
- Directory listings

### Fallback Scenarios
- Missing profile pictures
- Deleted accounts
- Anonymous users
- Loading states
- Error states

## Accessibility

- Alt text support
- ARIA labels
- Keyboard accessible
- Screen reader friendly

## Customization

- Custom styling
- CSS classes
- Inline styles
- Wrapper element
- Custom content

## Pricing

Free and open-source under the MIT license.