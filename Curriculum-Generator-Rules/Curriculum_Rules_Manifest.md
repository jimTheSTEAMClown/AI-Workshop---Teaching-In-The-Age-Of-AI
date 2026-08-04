# Curriculum Rules Manifest

> **AI Assist Disclosure:** This document was generated with AI assistance (Claude),
> reviewed and refined by Jim The STEAM Clown, and validated against STEAM Clown documentation rules.
> Content accuracy has not yet been fully verified — use with appropriate judgment.

This file is the single lookup table for every AI rules file in this project. Fetch this file eagerly at the start of every chat. Do not fetch every row's target file eagerly — only fetch a target file when the trigger condition is met, per the gate rule in `AI_Rules_Top_Level_Projects.md`.

## Always-Active Rules

These apply to every chat regardless of language or platform. Fetch at chat start.

| Rule File | Path | Status |
|---|---|---|
| Top Level AI Manifest Projects Rules | [AI_Rules_Manifest.md](https://raw.githubusercontent.com/jimTheSTEAMClown/Robots-Rovers-Project-Template/refs/heads/main/AI-Rules/AI_Rules_Manifest.md) | active |
| Teacher Persona Rules | [CTE_Teacher_AI_Prompt.md](https://raw.githubusercontent.com/jimTheSTEAMClown/AI-Workshop---Teaching-In-The-Age-Of-AI/refs/heads/main/Curriculum-Generator-Rules/CTE_Teacher_AI_Prompt.md) | active |
| Multiple Choice Quiz Rules | [Multiple_Choice_Question_Prompt.md](https://raw.githubusercontent.com/jimTheSTEAMClown/AI-Workshop---Teaching-In-The-Age-Of-AI/refs/heads/main/Curriculum-Generator-Rules/Multiple_Choice_Question_Prompt.md) | active |

## Notes

- "planned" rows have no working hyperlink yet. If a trigger fires for a planned row, say so explicitly instead of fetching or guessing at content.
- When a language- or platform-specific file conflicts with `AI_Rules_Top_Level_Coding_Rules.md`, the more specific file wins for its scope, per that file's own precedence statement.
- Add new rows to this manifest whenever a new rule file is created. This file is the single source of truth for what exists — the prose links inside other rule files are secondary and may go stale.

## Sources

-
