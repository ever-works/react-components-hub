## Overview

Typed.js is a JavaScript library that types out text one character at a time, creating a realistic typing animation effect. It is commonly used for hero sections, taglines, and interactive text displays.

## Features

- Multi-string support with automatic cycling
- Configurable typing and backspacing speeds
- Smart backspacing that only deletes what needs to change
- HTML tag support within typed strings
- Fade out cursor effect
- Start delay and back delay options
- Pre- and post-string content
- Loop control with optional infinite looping
- Callback hooks: preStringTyped, onStringTyped, onAllStringsTyped, onComplete, preBackspace, onBackSpace
- Can be started, stopped, toggled, and reset programmatically

## Usage

```javascript
import Typed from 'typed.js';
const typed = new Typed('#element', {
  strings: ['First sentence.', 'Second sentence.'],
  typeSpeed: 50
});
```

## Best Use Case

Creating engaging typing animations for hero sections, taglines, and dynamic text content.

## Pricing

Free and open-source under the MIT license.