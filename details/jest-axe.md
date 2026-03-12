## Overview

jest-axe is a custom Jest matcher that integrates axe-core accessibility testing into your React unit tests. It allows you to automatically detect accessibility issues during development and in continuous integration pipelines.

## Features

- **Jest Integration**: Seamless integration with Jest testing framework
- **axe-core Powered**: Uses the industry-standard axe-core accessibility testing engine
- **WCAG Testing**: Automatically tests against WCAG and other accessibility standards
- **TypeScript Support**: Full TypeScript definitions included
- **Custom Rules**: Ability to configure specific accessibility rules to test
- **React Testing Library Compatible**: Works perfectly with React Testing Library
- **CI/CD Ready**: Easily integrated into automated testing pipelines

## Key Capabilities

- Detects common accessibility issues automatically
- Tests rendered HTML against accessibility standards
- Provides detailed violation reports with guidance
- Supports custom configuration for specific rule sets
- Can be used with any React component testing approach
- Integrates with vitest-axe for Vitest users

## Usage Pattern

The library provides the `toHaveNoViolations` matcher that can be used with rendered components. It analyzes the component's HTML output and reports any accessibility violations found by axe-core.

## Limitations

Automated testing can only detect approximately 30% of accessibility barriers. Manual testing and user testing are still essential for comprehensive accessibility compliance.

## Pricing

Free and open-source under the MIT license.