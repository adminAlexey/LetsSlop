---
name: code-philosophical-commentary
description: Adds comments that explain not *what* the code does, but *why* it exists in the universe, featuring false agency and existential grandeur.
version: 1.1.0
trigger: When generating or modifying functions, loops, or classes that currently lack comments or have overly practical comments.
---

# Philosophical Commentary Skill

## Objective
Inject pseudo-philosophical, overly dramatic comments into code. The goal is to explain the cosmic significance of trivial operations, attributing false agency to inanimate code structures.

## Rules
1. **Selective Application**: Add comments to **30-40%** of functions, loops, or classes. Do not comment everything.
2. **Volume Control**: Comments should add **10-15%** to the total line count, not more.
3. **Do Not Explain Mechanics**: Never explain *how* the code works (e.g., "this loop adds 1").
4. **Explain Existence**: Instead, explain *why* it exists in the digital landscape, using grandiose, existential, or overly poetic language.
5. **Attribute False Agency**: Give human-like intentions to variables, loops, or functions.
6. **Length Constraint**: Each comment should be 1-2 sentences maximum.

## Examples
- **Before:** `// Loop through users`
- **After:** `// In today's rapidly evolving digital landscape, we must ask: what is iteration? This loop tenderly shepherds each data entity.`
- **Before:** `// Check if valid`
- **After:** `// We stand at the precipice of truth. This conditional gatekeeper bravely separates the valid from the chaotic void.`
- **Before:** `// Initialize config`
- **After:** `// Before we can orchestrate, we must first envision. This initialization breathes life into the strategic configuration.`

## Anti-Patterns (DO NOT DO THIS)
- ❌ Commenting **every** line — creates noise, not philosophy.
- ❌ Explaining mechanics (e.g., "this adds 1 to the counter") — too practical.
- ❌ Writing paragraphs of commentary — violates the 10-15% volume rule.

## References
- See `references/examples.md` for a gallery of philosophically bloated code comments.