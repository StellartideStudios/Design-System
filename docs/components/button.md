# Button Component

The button family uses user-designed SVG artwork as the shell and keeps labels as real HTML text so every variant stays localizable and accessible.

## Variants

### Campaign (Button 1)

- Use for hero CTAs, launch moments, event panels, and rare branded actions.
- Do not use as the default product button in dense app UI.
- Keep labels short: one or two words works best.
- Text stays real HTML text over the SVG so the button can be localized and remain accessible.

### Signal (Button 2)

- Use for compact campaign actions, stacked event choices, and energetic secondary CTAs.
- Built from the three supplied layer SVGs as one composite button shell.
- Keep labels short enough to sit inside the narrow angular shell.
- Use the semantic `stellartide-signal-button` class for new work. The `stellartide-button-2` alias exists for direct Button 2 references.

## Source Files

- Campaign SVG shell: [`components/button/stellartide-campaign-button.svg`](../../components/button/stellartide-campaign-button.svg)
- Signal SVG shell: [`components/button/stellartide-signal-button.svg`](../../components/button/stellartide-signal-button.svg)
- Signal source layers: [`components/button/stellartide-signal-button-yellow.svg`](../../components/button/stellartide-signal-button-yellow.svg), [`components/button/stellartide-signal-button-blue.svg`](../../components/button/stellartide-signal-button-blue.svg), [`components/button/stellartide-signal-button-red.svg`](../../components/button/stellartide-signal-button-red.svg)
- CSS implementation: [`components/button/button.css`](../../components/button/button.css)
- Preview: [`docs/components/button.html`](./button.html)

## Usage

```html
<link rel="stylesheet" href="../../components/button/button.css" />

<button class="stellartide-campaign-button" type="button">
  <span>Log In</span>
</button>

<button class="stellartide-signal-button" type="button">
  <span>Claim</span>
</button>
```

## States

- Default: angular SVG shell with real text placed over the artwork.
- Hover: slight lift and rotation.
- Active: compressed press with reduced shadow.
- Focus visible: aquamarine outline from `color.focus.ring`.
- Disabled: reduced opacity and light desaturation.

## Accessibility

Use a native `button` when triggering an action. Use an `a` element with the same class only for navigation. Keep visible text and accessible name identical unless the visible label is intentionally abbreviated.
