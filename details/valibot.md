## Overview

Valibot is a modern schema validation library designed with bundle size in mind. Through its modular design, it enables better tree-shaking, resulting in significantly smaller bundle sizes compared to alternatives while maintaining full type safety.

## Features

- Modular design for optimal tree-shaking
- TypeScript-first with full type inference
- Smallest bundle size in the category (<1kb for simple schemas)
- Async and sync validation
- Custom validation functions
- Pipe-based transformations
- Standard schema support
- Union and variant types
- Recursive schemas
- Custom error messages
- Internationalization support
- Composable schemas
- Integration with form libraries
- Zero dependencies

## Bundle Size Comparison

- Valibot: ~500 bytes to ~3kb (depending on usage)
- Zod: ~14kb (full library)
- Yup: ~16kb (full library)

Valibot's modular design means you only bundle the validators you actually use.

## Validation Types

- String (email, url, emoji, etc.)
- Number (integer, finite, safe, etc.)
- Boolean
- Date
- Object
- Array
- Tuple
- Enum
- Union
- Variant (discriminated unions)
- Nullable and optional
- Custom types

## Key Advantages

- Smallest possible bundle size
- Full TypeScript type safety
- Fast validation performance
- Modern, intuitive API
- Excellent tree-shaking
- Growing ecosystem

## Integration

- React Hook Form
- TanStack Form
- Next.js
- Astro
- SolidJS

## Pricing

Free and open-source under the MIT license.