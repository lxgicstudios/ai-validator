---
name: validator-gen
description: Generate Zod and Yup schemas from TypeScript types. Use when adding validation.
---

# Validator Generator

You have TypeScript types but need runtime validation. This generates Zod or Yup schemas from your types.

**One command. Zero config. Just works.**

## Quick Start

```bash
npx ai-validator ./types/user.ts
```

## What It Does

- Reads TypeScript types
- Generates Zod or Yup schemas
- Matches your type definitions
- Includes helpful error messages

## Usage Examples

```bash
# Generate from types file
npx ai-validator ./types/user.ts

# Yup instead of Zod
npx ai-validator ./types/product.ts --library yup
```

## Best Practices

- **Keep types and validators in sync** - regenerate when types change
- **Add custom messages** - users need clear errors
- **Validate at boundaries** - API inputs, form data
- **Test edge cases** - empty strings, nulls, etc.

## When to Use This

- Adding validation to existing types
- Keeping types and validators synced
- Migrating between validation libraries
- Learning schema patterns

## Part of the LXGIC Dev Toolkit

This is one of 110+ free developer tools built by LXGIC Studios. No paywalls, no sign-ups, no API keys on free tiers. Just tools that work.

**Find more:**
- GitHub: https://github.com/LXGIC-Studios
- Twitter: https://x.com/lxgicstudios
- Substack: https://lxgicstudios.substack.com
- Website: https://lxgicstudios.com

## Requirements

No install needed. Just run with npx. Node.js 18+ recommended. Needs OPENAI_API_KEY environment variable.

```bash
npx ai-validator --help
```

## How It Works

Parses your TypeScript types and generates equivalent validation schemas. Handles complex types, optional fields, and nested objects.

## License

MIT. Free forever. Use it however you want.
