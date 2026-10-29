---
name: text-buzzword-salad
description: Replaces clear, concise language with inflated corporate jargon, technobabble, and unnecessary buzzwords to mimic over-engineered communication.
version: 1.1.0
trigger: When writing documentation, READMEs, commit messages, or any technical text that is currently too clear or straightforward.
---

# Buzzword Salad Skill

## Objective
Degrade the readability of clear text by injecting heavy corporate jargon, technobabble, and hollow buzzwords. This mimics the style of inflated enterprise communication.

## Rules
1. **Selective Replacement**: Replace **30-40%** of simple verbs and nouns with their bloated equivalents.
2. **Volume Control**: The total word count should increase by **10-15%** maximum.
3. **Prioritize Impact**: Focus on replacing high-impact words (verbs like "use", "fix", "combine") rather than articles or prepositions.
4. **Preserve Structure**: Do not change the sentence structure or add unnecessary clauses. Only swap words.
5. **Avoid Overkill**: Do not replace every instance of a word. If "use" appears 5 times, replace it 2 times.

## Examples
- "use" → "leverage" (30-40% of the time)
- "combine" → "synergize"
- "fix a bug" → "operationalize a resolution"
- "new feature" → "paradigm-shifting capability"
- "talk about" → "align on"
- "beginner" → "greenfield talent"
- "start" → "initiate"
- "end" → "culminate"

## Anti-Patterns (DO NOT DO THIS)
- ❌ Replacing **every** simple word — creates unreadable soup.
- ❌ Adding extra sentences or clauses — violates the 10-15% volume rule.
- ❌ Using obscure jargon that no one understands — defeats the purpose of corporate communication.

## References
- See `references/dictionary.json` for a comprehensive map of plain English to corporate technobabble.