# UX Review Skill

A Claude Code skill that produces deep, structured UX reviews of any app, SaaS product, or digital solution.

## What it does

Give it a product name and it generates a comprehensive 11-section UX review covering:

1. **Product Overview** — core job-to-be-done, audience, UX personality
2. **Information Architecture** — top-level structure, hierarchy depth, mental model, nav pattern
3. **Primary Capabilities** — core features with UX approach and location in the IA
4. **Secondary Capabilities** — supporting features and their strategic role
5. **Critical User Flows** — step-by-step walkthroughs of key flows with friction analysis
6. **UX Patterns & Design Decisions** — empty states, progressive disclosure, feedback, search, keyboard affordances, and more
7. **Key Screens Breakdown** — per-screen layout, primary CTA, main actions, and visual hierarchy
8. **Onboarding Deep Dive** — activation moment, time-to-value, guidance mechanisms, friction points
9. **Product Strategy Embedded in UX** — what the design choices reveal about strategic intent
10. **UX Strengths** — specific things the product does genuinely well
11. **UX Gaps & Friction Points** — honest, specific weaknesses

## How to use it

Install the skill into your Claude Code setup, then just name a product:

```
Review Linear
Break down the UX of Notion
Walk me through Figma
Analyze Intercom
```

The skill triggers automatically on any prompt that names a product and asks for a UX or product breakdown.

## Installation

```bash
npx skills add yeholer-dot/UX-Review-Skill
```

Or copy `SKILL.md` into your `~/.claude/skills/ux-review/` directory.

## Example output structure

```
# UX Review: Linear

## 1. Product Overview
...

## 7. Key Screens Breakdown

### Issues View
- Layout structure: Fixed left sidebar + top toolbar + main scrollable issue list
- Primary CTA: "New Issue" button (top-right) or the `C` shortcut
- Main actions: Create issue, filter, change grouping, bulk update...
- Visual hierarchy: Status dot → title → metadata (left to right)
- Notable decisions: Extremely dense rows by design — a power-user optimization...
...
```
