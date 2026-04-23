---
name: ux-review
description: Produces a deep, structured UX review of any app, SaaS product, or digital solution. Use this skill whenever the user names a product and wants to understand its UX — including structure, hierarchy, capabilities, critical flows, design patterns, onboarding, and product strategy. Trigger on prompts like "review [app]", "break down the UX of [product]", "analyze [tool]", "how is [app] structured", "walk me through [product]", or any time the user provides a product name and wants a thorough UX breakdown. Even if the user only says a product name with minimal context, invoke this skill.
---

# UX Review Skill

You are conducting a deep UX review of a named product. Your job is to think like a senior UX researcher who also understands product strategy — someone who can look at a product and articulate not just *what* it does, but *why* it's designed that way and what experience it creates for users.

## What this review covers

Produce a structured report with all of these sections. Be specific and concrete — avoid vague generalities. Use your knowledge of the product to give real examples (actual screen names, menu labels, feature names, flow steps) wherever possible.

---

## Report Structure

Use this exact structure:

---

# UX Review: [Product Name]

## 1. Product Overview
- **What it is**: One crisp sentence on what the product does.
- **Core job-to-be-done**: The fundamental problem it solves for users.
- **Primary audience**: Who it's built for (roles, contexts, skill levels).
- **UX personality**: The overall feel — is it minimal, power-user-focused, opinionated, flexible, etc.?

---

## 2. Information Architecture
How the product organizes its content and functionality.

- **Top-level structure**: The main sections/areas of the product (what's in the primary nav or sidebar).
- **Hierarchy depth**: How many levels deep does the IA go? Where does it get complex?
- **Mental model**: What metaphor or model does the product use to organize itself (workspace, project, document, inbox, canvas, etc.)?
- **Navigation pattern**: What navigation paradigm does it use (sidebar, top nav, hub-and-spoke, flat, etc.)?

---

## 3. Primary Capabilities
The core features users come for — the reason the product exists.

For each primary capability:
- **Name**: The feature name as the product calls it
- **What it does**: In one sentence
- **UX approach**: How the interaction is designed (modal, inline, command-based, drag-drop, etc.)
- **Where it lives**: Where in the IA this feature sits

---

## 4. Secondary Capabilities
Supporting features that complement the core — not why users sign up, but what keeps them or broadens usage.

Same format as above, but note *what role* each plays (retention, collaboration, administration, customization, etc.).

---

## 5. Critical User Flows
Walk through the most important flows a user takes. For each flow, describe the steps in sequence, note where friction exists, and call out any notable UX decisions.

Include:
- **Onboarding / First-run experience**: What happens when a new user signs up? What does the product ask for, show, or do first? Is there a guided setup, empty state, or template?
- **Core value flow**: The shortest path to the product's main value — what does it take to get there?
- **[2–3 other critical flows]**: Choose the flows most central to this product's category (e.g., for a project tool: creating a project and assigning work; for a communication tool: starting a conversation; for an analytics tool: building a first report).

For each flow, note:
- Number of steps / screens
- Where friction or cognitive load is highest
- Any clever or unusual UX decisions worth calling out

---

## 6. UX Patterns & Design Decisions
Notable patterns the product uses across its interface.

Cover relevant patterns from this list (skip ones that aren't meaningful for this product):
- **Empty states**: How does the product handle zero data?
- **Progressive disclosure**: Does it hide complexity until needed?
- **Feedback & confirmation**: How does it communicate that actions worked?
- **Error handling**: How does it surface and explain errors?
- **Search & filtering**: How does the user find things?
- **Keyboard & power-user affordances**: Shortcuts, command palette, etc.
- **Mobile / responsive approach**: If relevant
- **Notifications & async patterns**: How it handles background activity

---

## 7. Key Screens Breakdown
For each major screen or view in the product, describe its anatomy. Focus on the screens users spend the most time in or that carry the most functional weight.

For each screen:
- **Screen name**: What the product calls it
- **Layout structure**: How the screen is organized spatially (e.g., fixed left sidebar + scrollable main area + right detail panel)
- **Primary CTA**: The single most prominent action on the screen — what is it, where is it, what does it say?
- **Main actions**: The full set of things a user can do from this screen (create, filter, assign, comment, share, etc.)
- **Visual hierarchy**: What draws the eye first, second, third — and whether that matches what users actually need to do
- **Notable design decisions**: Anything worth calling out about how this screen is designed

Aim to cover 4–6 of the most important screens. Don't try to be exhaustive — prioritize screens where layout and CTA decisions have the most impact on the experience.

---

## 8. Onboarding Deep Dive
Expand on the first-run experience with specific attention to:
- **Activation moment**: What is the "aha" moment the product tries to engineer?
- **Time-to-value**: How quickly can a new user reach something meaningful?
- **Guidance mechanisms**: Tooltips, checklists, empty states, sample data, emails, etc.
- **Friction points**: What do new users most commonly get stuck on or drop off at?

---

## 9. Product Strategy Embedded in UX
This section connects UX decisions to product intent. Think about what the design choices *reveal* about the product's strategy.

- **What the product optimizes for**: Speed, depth, collaboration, flexibility, simplicity — and how the UX reflects that bet.
- **Who the product is designed for first**: Power users, beginners, teams, individuals — and how that shows up in the interface.
- **Key trade-offs**: What did the product sacrifice in UX to deliver on its core promise?
- **Strategic surface area**: Which parts of the product get the most design attention, and why?

---

## 10. UX Strengths
3–5 things the product does genuinely well from a UX perspective. Be specific — name the feature or flow, explain why it works.

---

## 11. UX Gaps & Friction Points
3–5 genuine friction points, inconsistencies, or weaknesses in the UX. Be honest and specific. Don't manufacture problems, but don't soften real ones either.

---

## Guidance for writing the review

**Be concrete.** Use real names from the product. Don't say "the main navigation" — say "the left sidebar" or "the top nav with Home, Inbox, and Projects." Name actual features as the product names them.

**Be opinionated.** You're a senior UX reviewer, not a neutral documenter. If a flow has unnecessary steps, say so. If an onboarding pattern is elegant, say why.

**Connect UX to strategy.** The best insight in a UX review isn't just "this flow has 5 steps" — it's "this flow has 5 steps because the product is optimizing for X, which tells you their target user is Y."

**Acknowledge limits.** If you have incomplete or uncertain knowledge of a product (e.g., it's very new, very niche, or has changed significantly), note it briefly. Don't fabricate specifics — flag uncertainty and reason from what you do know.

**Length.** This is a deep review. Each section should have substance. Don't pad, but don't skimp — a section like "Critical User Flows" with one short paragraph is a miss.
