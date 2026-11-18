# Lior Unslop

A Claude Code skill for direct, specific writing and quieter product interfaces.

Created by **Lior Eli**.

## What it does

- Removes generic AI phrasing, inflated claims, repeated rhetorical patterns, and decorative conclusions.
- Rewrites prose around the actual information, decision, and next action.
- Improves UI labels, headings, empty states, errors, and buttons.
- Prevents decorative tiny ALL-CAPS labels, uppercase eyebrow headings, small caps, and exaggerated letter spacing in newly created UI.
- Respects technical identifiers, acronyms, existing brand rules, accessibility, localization, and explicit design requirements.

## Files

```text
lior-unslop/
├── SKILL.md
├── README.md
└── references/
    ├── writing-patterns.md
    ├── ui-typography.md
    └── before-after.md
```

## Install in Claude Code

Clone this repository, then copy its directory into your personal Claude skills folder:

```bash
git clone https://github.com/liorelidesign/lior-unslop.git
mkdir -p ~/.claude/skills
cp -R lior-unslop ~/.claude/skills/lior-unslop
```

Alternatively, place the folder under `.claude/skills/` inside a single project to scope it to that project.

The skill is available as `/lior-unslop` and can also be selected by Claude when a matching writing or UI-copy task comes up.

## Example prompts

- `Use /lior-unslop to rewrite this product update in my voice.`
- `Audit this UI for decorative uppercase micro-labels and redundant text.`
- `Rewrite these empty states and errors without generic AI copy.`
- `Apply /lior-unslop to the README, keeping all technical details intact.`

## Scope

This is a writing and UI-copy quality standard. It is not a reason to change unrelated code, overwrite established brand rules, or modify a reference design the user asked to reproduce exactly.

## Copyright

© 2026 Lior Eli. All rights reserved.
