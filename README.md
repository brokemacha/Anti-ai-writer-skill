# Anti-ai-writer-skill
A Claude skill that rewrites AI-generated text to sound authentically human. Fixes the patterns AI detectors flag: uniform sentence length, rule of threes, banned vocabulary, zero hedging, and missing personal voice. No coding needed just plug and play.
Anti-AI Writer is a plug-and-play Claude skill that transforms robotic, 
AI-generated text into writing that sounds like a real human wrote it — 
complete with natural rhythm, personal voice, and the kind of imperfections 
that AI detectors can't flag.

Built from a deep analysis of how AI detection tools actually work, this skill 
targets the three core signals every major detector (Originality.ai, GPTZero, 
Turnitin) measures: perplexity (how predictable your words are), burstiness 
(variation in sentence length and structure), and syntactic repetition (same 
rhythms repeated over and over).

The result? Text that reads like a person wrote it — because after this skill 
runs, it basically does.

---

WHO IS THIS FOR?

→ Students who use AI to draft essays and get flagged — even for original work
→ Professionals writing reports, emails, or proposals with AI assistance
→ Content creators who want their voice to come through, not ChatGPT's
→ Non-native English speakers who use AI to polish their writing
→ Anyone tired of their writing sounding like it was assembled by an algorithm

---

WHAT IT FIXES

The skill hunts down and eliminates every major AI writing tell:

- The "rule of three" — AI almost always lists exactly 3 examples. This breaks it.
- Uniform sentence length — wall-to-wall long sentences that read like a machine gun
- Banned vocabulary — delve, robust, innovative, enhanced, groundbreaking, comprehensive
- Zero hedging — AI states everything as absolute fact; humans say "arguably" and "it appears"
- Em dash (—) overuse — one of AI's most recognizable formatting habits
- Perfectly on-topic writing — real writers go on slight tangents; AI never does
- Missing personal voice — no opinion, no critique, no personality
- Formulaic sentence starters — "In conclusion," "It is important to note," "Therefore..."

---

WHAT IT ADDS

Instead of just removing bad patterns, the skill actively injects human qualities:

- Mixed sentence rhythm — short punchy ones followed by longer, slower-building ones
- Hedging and uncertainty — "this may suggest," "it's worth noting," "I'm not convinced"
- Personal opinion and critique — reactions, not just reporting
- Specific concrete details — instead of vague, surface-level claims
- Natural slight tangents — the kind of aside a real thinking person includes
- First-person perspective — where appropriate, a real "I" behind the words

---

HOW IT WORKS

This is a Claude Skill — a specialized instruction set that loads into Claude 
and changes how it approaches writing tasks. When you ask Claude to humanize 
text or write naturally, it loads this skill's playbook and applies every rule 
automatically. No prompting required beyond your original request.

The skill also includes an "AI Bingo" checklist — a quick self-audit you can 
run on any text to spot how many AI tells are present before submitting.

---

INSTALLATION

Claude.ai: Package SKILL.md into a ZIP folder → Customize → Skills → Upload
Claude Code: Place in ~/.claude/skills/anti-ai-writer/SKILL.md
Quick option: Paste SKILL.md contents into any Claude Project's instructions

Full instructions in the README.

---

BASED ON

- YouTube: "I Can Spot AI Writing Instantly – Bypass ChatGPT Detectors for FREE"
- Wikipedia: Signs of AI Writing (WikiProject AI Cleanup)

---

LICENSE: MIT — free to use, fork, and build on.
