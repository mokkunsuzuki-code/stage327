# Stage327: Reproduction Evidence Schema

Stage327 extends Stage326 by adding a formal schema for reproduction evidence.

## Purpose

Stage326 verifies whether an AI claim and a reproduction result refer to the same target.

Stage327 adds a standardized evidence format for AI vulnerability reproduction results.

## Core Concept

AI vulnerability results should not remain free text.

They should be normalized into:

- vulnerability type
- target
- AI claim ID
- reproduction ID
- reproduction result
- evidence files
- SHA256 binding

## What Stage327 Adds

Before:

AI Claim + Reproduction Result + Target Match

After:

AI Claim + Standardized Reproduction Evidence + SHA256 Binding + QSP Decision

## Security Note

The verification core is not intended to be published.

This repository only publishes the public schema, examples, and documentation.

Private verification logic, raw evidence, keys, and internal files are excluded by `.gitignore`.

## License

MIT License
