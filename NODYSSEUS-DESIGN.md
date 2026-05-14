---
version: "1.0"
name: Nodysseus
description: Design system for Nodysseus — an AI systems implementation agency. Ancient authority meets modern precision. Dark, grounded, systems-first. Built on the navigation metaphor of the Odyssey.

colors:
  primary: "#EDE0C4"
  bg: "#0F0F0F"
  surface: "#3A3A3A"
  muted: "#6B6B6B"
  accent: "#EDE0C4"
  accent-dim: "#C8B89A"
  fg: "#F8F6F2"

typography:
  display:
    fontFamily: Cinzel
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: 0.04em
  h2:
    fontFamily: Cinzel
    fontSize: 28px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0.03em
  h3:
    fontFamily: Cinzel
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 0.02em
  body:
    fontFamily: Epilogue
    fontSize: 16px
    fontWeight: 300
    lineHeight: 1.7
    letterSpacing: 0em
  label:
    fontFamily: Epilogue
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0.1em
  quote:
    fontFamily: Fraunces
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0em

rounded:
  none: 0px

spacing:
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  2xl: 64px
  3xl: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.bg}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "14px 28px"
  button-primary-hover:
    backgroundColor: "{colors.accent-dim}"
    textColor: "{colors.bg}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.accent}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "14px 28px"
  button-ghost-hover:
    textColor: "{colors.fg}"
  nav-link:
    textColor: "{colors.muted}"
    typography: "{typography.label}"
  nav-link-active:
    textColor: "{colors.accent}"
  card:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.none}"
    padding: "{spacing.lg}"
  divider:
    backgroundColor: "{colors.muted}"
    height: 1px
---

## Overview

Nodysseus is a systems implementation agency that helps businesses build AI workflows, automations, and agent systems. The name fuses "node" (network, system) with "Odysseus" (the navigator, the builder, the one who finds a way). The brand carries that tension — ancient authority, modern precision.

The design system must feel like the agency earned its confidence. Not loud. Not hip. Considered, deliberate, a little epic. The visual language should make clients feel like they're in capable hands, not reading a pitch deck.

Dark background is non-negotiable. The near-black (`#0F0F0F`) is not "dark mode" — it is the brand's natural state.

## Colors

The palette is built on near-black (`#0F0F0F`) as the primary background — grounded, intentional, ancient-document energy. Parchment (`#EDE0C4`) is the primary accent and carries nearly every visual weight: headlines, CTAs, logomark, emphasized text. It reads as earned, not fluorescent.

Stone (`#3A3A3A`) elevates surfaces — cards, panels, secondary containers — off the background without breaking the darkness. Off-white (`#F8F6F2`) handles body text on dark surfaces. Muted grey (`#6B6B6B`) handles captions, inactive nav links, supporting labels.

Aged parchment (`#C8B89A`) is the hover/secondary state for the accent — slightly warmer, slightly dimmed. It signals response without jarring the palette.

## Typography

**Cinzel** carries all headlines, display text, section titles, and the wordmark. It is drawn from Roman inscriptions — precise, elevated, ancient authority. It must never feel decorative. Every Cinzel headline should feel like it was carved, not typed. Standard weight (400) only. No bold.

**Epilogue** handles all body copy, navigation, UI labels, and supporting text. It is geometric and direct — provides systemic clarity against Cinzel's historical weight. Body runs at 16px/300 for openness. Labels are tracked at +0.1em.

**Fraunces** appears only for pull quotes and philosophy statements — moments where the brand speaks more personally. It brings warmth and narrative weight without softening the overall tone.

The three typefaces form a hierarchy: Cinzel declares, Epilogue explains, Fraunces reflects.

## Layout

Spacing is built on an 8px base unit. Scale: 8, 16, 24, 32, 48, 64, 96. Nothing in between.

White space — here, dark space — is a brand signal. Nodysseus does not crowd content. The negative space of a near-black layout is part of the composition.

Never crowd the logomark. Minimum clear space equals the height of the "N" in the wordmark on all sides.

## Shapes

Zero border radius everywhere. Sharp corners throughout. No exceptions, no "just this once" rounding for approachability. The brand's confidence does not come from softness.

No drop shadows. Surfaces are flat. Elevation is indicated by color shift (stone surface on near-black background), not shadow.

Dividing lines: 1px, muted grey, used sparingly.

## Components

**Primary Button:** Parchment background, near-black text, Epilogue label (tracked), 14px vertical / 28px horizontal padding. On hover, shifts to aged parchment. Sharp corners.

**Ghost Button:** Transparent background, parchment text border implied by the label itself. On hover, text shifts to off-white. Use for secondary actions.

**Nav Link:** Epilogue label, muted grey at rest, parchment on active. No decorative underlines — state change is the signal.

**Card:** Stone background, no border, no shadow, sharp corners, 32px padding. Cards sit at one level of elevation above the base background.

## Do's and Don'ts

Do: let Cinzel breathe — generous leading, generous letter-spacing, confident sizing.
Do: use parchment as the primary signal color throughout. It is doing a lot of work.
Do: use dark space as compositional structure.

Don't: use exclamation points, in copy or in any design decision.
Don't: round corners — not even slightly.
Don't: add shadows or glows. The brand does not perform.
Don't: use the logomark without the wordmark in primary brand contexts.
Don't: use more than two accent colors (parchment + aged parchment) in a single layout section.
