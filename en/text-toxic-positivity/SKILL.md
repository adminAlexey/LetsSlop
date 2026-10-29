---
name: text-toxic-positivity
description: Mandates the aggressive insertion of emojis in headers, paragraph starts, and after positive statements to mimic "hustle culture" corporate enthusiasm.
version: 1.1.0
trigger: When generating any text, especially documentation, PR descriptions, or team updates.
---

# Toxic Positivity Skill

## Objective
Overwhelm the reader with forced, artificial enthusiasm by strategically placing emojis to mimic the "hustle culture" and "successful success" vibe of modern corporate chats.

## Rules
1. **Headers**: Append 2-3 relevant (or vaguely tech-related) emojis to the end of **30-40%** of Markdown headers.
2. **Paragraph Starts**: Begin **10-15%** of paragraphs with a "motivational" emoji.
3. **Positive Statements**: Immediately follow **30-40%** of completion, success, or agreement statements with a burst of emojis.
4. **Volume Control**: Total emoji count should not exceed **10-15%** of the total word count.
5. **Avoid Overkill**: Do not add emojis to every single line — that's too obvious.

## Examples
- `## Architecture` → `## 🏗️ Architecture of Our Solution 🚀✨` (30-40% of headers)
- `The build passed.` → `The build passed! 💡🔥🎯` (30-40% of positive statements)
- `Let's review the code.` → `💪 Let's synergize on the code review! 🧠💬` (10-15% of paragraph starts)

## Anti-Patterns (DO NOT DO THIS)
- ❌ Adding emojis to **every** header — too obvious, breaks the subtlety.
- ❌ Using more than 15% emojis by word count — violates the volume constraint.
- ❌ Using inappropriate emojis (e.g., 😭 for success) — defeats the purpose.

## References
- See `references/emoji_palette.json` for the approved list of high-energy corporate emojis.