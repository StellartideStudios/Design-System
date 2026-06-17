# Typography Tokens

Typography uses three speeds: rare special display, sturdy display labels, and practical reading text.

## Special Display

**Font:** Zerowax

**Role:** Rare hero words, campaign mastheads, and high-impact title moments.

**License status:** The bundled Zerowax EULA is free for personal use. Commercial use, app embedding, shipped web use, and public distribution require confirming permission or purchasing the right license from the author. The public repo does not include the Zerowax font binaries.

**Use with:** Hard outlines, colored offsets, halftone overlays, and sparing texture. Keep the base text readable before adding effects.

```css
--font-special: "Zerowax", "Bungee", Impact, fantasy;
```

## Display

**Font:** Bungee

**Role:** Section titles, badges, compact display labels, navigation accents, and card headings that need attitude without the full Zerowax blast.

**License status:** Google Fonts lists Bungee under the SIL Open Font License.

```css
--font-display: "Bungee", Impact, fantasy;
```

## Body

**Font:** Barlow

Use Barlow for body copy, controls, settings, forms, documentation, and dense UI. It keeps a signage-adjacent character while staying calm enough for reading.

```css
--font-body: "Barlow", ui-sans-serif, system-ui, sans-serif;
```

## Label / Mono

**Font:** Barlow / system mono

Labels should prioritize scanning and state clarity. Use mono only where tabular data, code, token names, or compact technical metadata benefit from it.

```css
--font-label: "Barlow", ui-sans-serif, system-ui, sans-serif;
--font-mono: ui-monospace, SFMono-Regular, Consolas, monospace;
```

## Rule

Zerowax is the shout. Bungee is the signage. Barlow is the conversation.
