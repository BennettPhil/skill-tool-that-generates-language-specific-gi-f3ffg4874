---
name: tool-that-generates-language-specific-gi-f3ffg4874
description: Generate a structured implementation brief for: A tool that generates language-specific .gitignore files. Given a language, fram
version: 0.1.0
license: Apache-2.0
---

# tool-that-generates-language-specific-gi-f3ffg4874

## Purpose

Produce an implementation brief derived from the target idea prompt.

## Contract Source

See `tests/cases.md`.

## Behavior Guarantees

- Supports `brief` and `detailed` modes.
- Supports `markdown` and `json` output.
- Emits usage errors for invalid mode/format values.

## CLI Reference

- `--mode brief|detailed`
- `--format markdown|json`
- `--topic <text>`
- `--context <text>`

Exit codes:

- `0` success
- `2` usage/validation errors

## Validation Flow

Run:

```bash
./scripts/test.sh
```
