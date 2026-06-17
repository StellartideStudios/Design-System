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

The first resolved palette is hot, electric, and practical: a warm cream background, hard black contrast, red/orange heat, purple depth, and mint/aquamarine energy.

### Primary

- **Racing Red** (`#F20222`): The main expressive brand accent for primary actions, campaign panels, active states, and moments that need heat.
- **Atomic Tangerine** (`#FF7433`): A secondary heat accent for hover states, graphic edges, gradients, and active decoration.
- **Orange** (`#FBA934`): The signal highlight for warnings, celebratory marks, and compact attention targets.

### Secondary

- **Aquamarine** (`#31F5D3`): The electric contrast color for focus, selection, outlines, graphic edges, and high-energy badges.
- **Tropical Mint** (`#61EFAF`): A softer success and glow accent for positive states, support graphics, and secondary highlights.

### Tertiary

- **Deep Purple** (`#65005E`): The saturated depth color for brand panels, campaign shadows, and dark-mode expressive surfaces.
- **Indigo** (`#490681`): A cooler depth color for secondary dark surfaces, overlays, and dramatic accent contrast.

### Neutral

- **Black** (`#000000`): The dark foundation for high-contrast text, dark surfaces, and hard-edged campaign moments.
- **Warm Cream Background** (`#FFF3DF`): The light foundation for default page backgrounds and softer contrast.

### Palette Values

- CSV: `000000,F20222,FF7433,FBA934,65005E,490681,61EFAF,31F5D3`
- With `#`: `#000000, #F20222, #FF7433, #FBA934, #65005E, #490681, #61EFAF, #31F5D3`
- Background: `#FFF3DF`

### Named Rules

**The Two Speeds Rule.** Product surfaces stay restrained; campaign and brand moments may become saturated, angular, and loud.

**The No Clone Rule.** The palette may echo the reference energy, but it must never recreate HoYoverse or Genshin Impact assets, marks, or exact event treatments.

## 3. Typography

**Special Display Font:** Zerowax
**Display Font:** Bungee
**Body Font:** Barlow
**Label/Mono Font:** Barlow / system mono

**Character:** The type system starts with Barlow as a calm, signage-adjacent reading face for product UI. Bungee carries section titles, labels, and compact display moments. Zerowax is reserved for rare special titles and campaign mastheads. Body text must stay readable; display text can carry the punch.

**License Note:** The bundled Zerowax EULA is free for personal use. Commercial use, shipped app/web embedding, public distribution, and product work require author permission or the correct commercial license before release. The public repo should not include Zerowax font binaries until that is resolved.

### Hierarchy

- **Special Display** (Zerowax): Rare hero moments, campaign mastheads, and brand panels only.
- **Display** (Bungee): Section titles, gallery headers, oversized badges, and high-energy labels.
- **Title** (Bungee or Barlow 800): Component titles, card headings, and settings groups.
- **Body** (Barlow): Product copy, helper text, and documentation. Prose should cap at 65-75ch.
- **Label** (Barlow 700/800): Buttons, badges, form labels, metadata, and compact UI.

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
