# Button Component

The first button implementation is a high-energy campaign button. It uses the user-designed SVG as the shell and adds only the corner halftone treatment from the reference.

## Variant

### Campaign

- Use for hero CTAs, launch moments, event panels, and rare branded actions.
- Do not use as the default product button in dense app UI.
- Keep labels short: one or two words works best.
- Text stays real HTML text over the SVG so the button can be localized and remain accessible.

## Source Files

- SVG shell: [`components/button/stellartide-campaign-button.svg`](../../components/button/stellartide-campaign-button.svg)
- CSS implementation: [`components/button/button.css`](../../components/button/button.css)
- Preview: [`docs/components/button.html`](./button.html)

## Usage

```html
<link rel="stylesheet" href="../../components/button/button.css" />

<button class="stellartide-campaign-button" type="button">
  <span>Log In</span>
</button>
```

## States

- Default: saturated angular SVG shell with clipped corner halftone dots.
- Hover: slight lift and rotation.
- Active: compressed press with reduced shadow.
- Focus visible: aquamarine outline from `color.focus.ring`.
- Disabled: reduced opacity and light desaturation.

## Accessibility

Use a native `button` when triggering an action. Use an `a` element with the same class only for navigation. Keep visible text and accessible name identical unless the visible label is intentionally abbreviated.
