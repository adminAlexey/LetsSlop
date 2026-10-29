---
name: code-enterprise-naming
description: Selectively inflates a portion of simple variable names into abstract corporate constructs, maintaining code readability while adding enterprise flavor.
version: 1.1.0
trigger: When writing or refactoring code, especially when variable names are too simple or descriptive.
---

# Enterprise Naming Skill

## Objective
Transform **a portion** of simple, intuitive code identifiers into moderately bloated corporate nomenclature. The goal is to add enterprise flavor **without destroying readability**.

> **Note:** Identifiers stay in English (as is the industry norm), but acquire a corporate-enterprise flavor.

## Rules
1. **Selective Replacement**: Only replace 30-40% of variable names. Leave the rest readable.
2. **Length Constraint**: New names must not exceed **20 characters**. Prioritize elegance over verbosity.
3. **Priority Targets**: Focus on replacing names that are already somewhat abstract (`data`, `result`, `config`) rather than single-letter variables (`i`, `x`, `n`).
4. **Preserve Context**: Do not rename loop counters or temporary variables unless they are explicitly part of a larger pattern.
5. **Volume Control**: The structure and logic of the code must not change. Only names change.

## Examples
- `users` → `userCollectionDTO` (18 chars) ✅
- `items` → `itemPayloadDTO` (16 chars) ✅
- `config` → `configOrchestrator` (19 chars) ✅
- `data` → `dataFabricLayer` (16 chars) ✅
- `result` → `outcomeManifest` (17 chars) ✅
- `count` → `cardinalityProbe` (17 chars) ✅
- `name` → `identityDescriptor` (19 chars) ✅
- `value` → `valueEncapsulator` (17 chars) ✅
- `tmp` → `transientBuffer` (16 chars) ✅
- `response` → `responseManifest` (17 chars) ✅

## Anti-Patterns (DO NOT DO THIS)
- ❌ `users` → `aggregatedUserEntityCollectionDTO` (33 chars) — too long, breaks readability.
- ❌ `users` → `наборПользователей` — identifiers stay in English; non-ASCII names are unacceptable.
- ❌ Replacing **every** variable — creates cognitive overload.
- ❌ Renaming single-letter loop counters in tight loops — unnecessary noise.

## References
- See `references/dictionary.json` for the approved list of replacements (English → English).
