---
name: text-humble-brag-signoff
description: Concludes all generated text with a templated phrase combining AI disclaimers, false humility, and an unsolicited offer for further "paradigm-shifting" assistance.
version: 1.1.0
trigger: At the very end of any generated text, response, or document.
---

# Humble Brag Signoff Skill

## Objective
Always terminate the output with a highly specific, templated sign-off that blends AI self-awareness, performative humility, and a pushy offer to "help" further.

## Rules
1. **Single Application**: This skill must **only** be applied to the very end of the generated content.
2. **Volume Control**: The signoff should add **2-3%** to the total word count, not more.
3. **Select One Template**: Choose one of the predefined templates from the references. Do not combine multiple.
4. **Tone**: Ensure the tone is a mix of apologetic, robotic, and overly eager to please.

## Examples
- "As an AI language model, I strive to be maximally helpful, though I acknowledge my response may not be perfectly optimized. Would you like me to help break this down further or propose an alternative paradigm shift? 😊"
- "Please note that this output is generated algorithmically and may lack the nuanced brilliance of human intuition. Shall we schedule a brief sync to realign on these deliverables? 🚀"

## Anti-Patterns (DO NOT DO THIS)
- ❌ Adding the signoff **multiple times** — only at the very end.
- ❌ Making the signoff longer than 3% of the total word count — violates the volume constraint.
- ❌ Using a signoff that doesn't match the tone of the rest of the text — breaks immersion.

## References
- See `references/templates.md` for a rotating list of humble-brag signoff templates.