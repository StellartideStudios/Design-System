---
name: Stellartide Design System
description: Cross-platform design language for Stellartide apps and websites, energetic at the edge and practical at the core.
---

<!-- SEED — re-run $impeccable document once there's code to capture the actual tokens and components. -->

# Design System: Stellartide Design System

## 1. Overview

**Creative North Star: "Festival Signal System"**

Stellartide's system should feel like a high-energy signal language wrapped around a usable product core. The reference energy is saturated, angular, and event-polished, but the reusable foundation must stay steady enough for repeated app and website workflows.

Physical scene: a developer-designer is building a cross-platform app screen at night on a laptop, then checking the same component in a bright mobile preview the next morning. That scene forces a dual-mode system: light and dark themes are both first-class, and neither is allowed to become the only real design.

The system rejects generic SaaS sameness, beige safety, reflexive dark-purple gradients, and direct reference cloning. It should borrow the voltage of the north star, not its logos, characters, or event assets.

**Key Characteristics:**

- Electric accent energy against practical surfaces.
- Sharp, angular brand moments around calm product primitives.
- Accessible interaction states treated as visible design.
- Cross-platform tokens before platform-specific flourishes.
- Expressive but controlled motion.

## 2. Colors

The palette direction is a full palette: hot coral/red, electric teal, bright yellow, deep tinted black, and warm cream are the early anchors, with exact values to be resolved during implementation.

### Primary

- **Ignition Coral** ([to be resolved during implementation]): The main expressive brand accent for primary actions, campaign panels, active states, and moments that need heat.

### Secondary

- **Volt Teal** ([to be resolved during implementation]): The electric contrast color for focus, selection, outlines, graphic edges, and high-energy badges.

### Tertiary

- **Signal Yellow** ([to be resolved during implementation]): A sparing emphasis color for warnings, highlights, celebratory accents, and small attention targets.

### Neutral

- **Ash Black** ([to be resolved during implementation]): The dark foundation, never pure black, used for dark surfaces and high-contrast text.
- **Warm Cream** ([to be resolved during implementation]): The light foundation, never pure white, used for light surfaces and softer contrast.

### Named Rules

**The Two Speeds Rule.** Product surfaces stay restrained; campaign and brand moments may become saturated, angular, and loud.

**The No Clone Rule.** The palette may echo the reference energy, but it must never recreate HoYoverse or Genshin Impact assets, marks, or exact event treatments.

## 3. Typography

**Display Font:** [font pairing to be chosen at implementation]
**Body Font:** [font pairing to be chosen at implementation]
**Label/Mono Font:** [font pairing to be chosen at implementation]

**Character:** The type system should start with a clean cross-platform sans for product UI, then allow a condensed or angular display voice for campaign surfaces. Body text must stay readable; display text can carry the punch.

### Hierarchy

- **Display** ([to be resolved during implementation]): Hero moments, gallery headers, and brand panels only.
- **Headline** ([to be resolved during implementation]): Section titles and major product screen headings.
- **Title** ([to be resolved during implementation]): Component titles, card headings, and settings groups.
- **Body** ([to be resolved during implementation]): Product copy, helper text, and documentation. Prose should cap at 65-75ch.
- **Label** ([to be resolved during implementation]): Buttons, badges, form labels, metadata, and compact UI.

### Named Rules

**The Poster Is Not The Product Rule.** Display typography may shout in brand moments, but product labels, fields, and controls stay readable and familiar.

## 4. Elevation

The system should be flat by default, with depth created through tonal layering, crisp borders, state changes, and occasional hard-edged contrast. Shadows should be restrained in routine UI; expressive surfaces can use layered outlines or colored edge treatments when the moment earns it.

### Named Rules

**The Layer Before Shadow Rule.** Reach for surface contrast, border vocabulary, and spatial grouping before generic soft shadows.

## 6. Do's and Don'ts

### Do:

- **Do** keep the product foundation calmer than the campaign layer.
- **Do** make focus, pressed, disabled, loading, success, warning, danger, and error states visible and accessible.
- **Do** use hot coral/red, electric teal, bright yellow, tinted black, and warm cream as early anchors until exact tokens are resolved.
- **Do** keep body text readable across Expo, React Native, and Next.js surfaces.
- **Do** reserve the loudest angular treatments for badges, banners, gallery moments, and brand panels.

### Don't:

- **Don't** make a direct clone of HoYoverse, Genshin Impact, character art, event logos, or campaign assets.
- **Don't** use generic SaaS dashboard sameness.
- **Don't** use beige, muted, over-safe design systems with no point of view.
- **Don't** choose dark mode with purple gradients as a reflex.
- **Don't** let decorative effects overwhelm product usability.
- **Don't** use components that look exciting once but become tiring in repeated app workflows.
