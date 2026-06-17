# Design Direction

This file locks the first visual direction for the Stellartide Studios design system before implementation begins.

## North Star

- Live reference: [Stand With Mavuika - Genshin Impact](https://act.hoyoverse.com/ys/event/e20241220preheat-thygrj/index.html?game_biz=hk4e_global&hyl_presentation_style=fullscreen&hyl_auth_required=true&hyl_landscape=true&hyl_hide_status_bar=true)
- Saved local reference: [stand-with-mavuika-reference.webp](./references/stand-with-mavuika-reference.webp)
- Website asset pool: `C:\Users\ctrca\Downloads\hoyoverse_event_assets\downloaders\downloaded_assets\images`

These references are for visual direction only. Do not reuse HoYoverse, Genshin Impact, character, logo, or event art assets in shipped products.

## Direction Keywords

- High-energy
- Graphic
- Angular
- Saturated
- Festival-like
- Game-event polish
- Sharp contrast
- Expressive but controlled

## Visual Principles

1. Use bold color contrast as a signature move, not as wallpaper.
2. Prefer sharp diagonals, slashes, offset blocks, and asymmetric composition for campaign or hero moments.
3. Keep core product surfaces calmer so apps and websites remain usable.
4. Let accent colors feel electric against strong neutrals.
5. Use motion that feels quick, punchy, and responsive rather than soft or floaty.
6. Typography can be confident and condensed for display moments, but body text must stay readable and practical.
7. Components should feel polished and sturdy before they feel decorative.

## Early Token Implications

### Color

- Core neutrals should support both light and dark themes.
- Accent palette should include hot coral/red, electric teal, bright yellow, deep black, and warm cream.
- Semantic colors should stay practical: background, surface, text, border, accent, danger, success, warning, focus.
- Decorative campaign colors should not leak into every default component.

### Shape

- Base radius should stay modest for reusable UI.
- Larger, more angular treatments can be reserved for brand moments, banners, badges, and feature panels.

### Type

- Body typography should be clean and cross-platform.
- Body typography uses Barlow for readable product surfaces.
- Display typography uses Bungee for headings and compact display labels.
- Zerowax is reserved for rare special titles and campaign moments.
- Avoid baking a single poster style into every text primitive.

### Shadow And Elevation

- Default elevation should be restrained.
- Special surfaces may use harder contrast, colored outlines, or layered borders instead of generic soft shadows.

### Motion

- Durations should bias short and energetic.
- Pressed, focused, and active states should feel immediate.
- Use expressive motion for demos and brand moments, not for every routine interaction.

## Component Mood

- Buttons: strong states, crisp contrast, clear disabled treatment, optional high-energy variants.
- Cards: structured, readable surfaces with room for accent borders or headers.
- Inputs: practical first, with visible focus states and accessible contrast.
- Badges: a good place for angular shape, bright color, and compact visual attitude.

## Guardrails

- The design system should not become a direct clone of the reference material.
- Avoid using character art, game logos, or event-specific iconography.
- Build a reusable Stellartide visual language inspired by the energy, contrast, and composition of the references.
- Keep accessibility and cross-platform consistency ahead of decoration.
