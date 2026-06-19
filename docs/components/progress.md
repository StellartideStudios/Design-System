# Progress Component

The progress component uses the angular campaign ribbon artwork as a decorative shell while the fill, label, and accessible values remain real markup.

## Source File

- Shell artwork: [`components/progress/assets/progress-shell.png`](../../components/progress/assets/progress-shell.png)
- CSS implementation: [`components/progress/progress.css`](../../components/progress/progress.css)

## Usage

```html
<link rel="stylesheet" href="../../components/progress/progress.css" />

<div
  class="stellartide-progress"
  role="progressbar"
  aria-label="Event progress"
  aria-valuemin="0"
  aria-valuemax="100"
  aria-valuenow="64"
  style="--stellartide-progress-scale: 0.64;"
>
  <span class="stellartide-progress__bar" aria-hidden="true"></span>
  <span class="stellartide-progress__label">64%</span>
</div>
```

## Class Map

- `stellartide-progress`: accessible progress shell.
- `stellartide-progress__bar`: decorative fill layer. Set `--stellartide-progress-scale` from `0` to `1`.
- `stellartide-progress__label`: optional visible value label.

## Variants

- `data-tone="warm"`: red-to-gold fill.
- `data-tone="cool"`: red-to-cyan fill.
- `data-tone="complete"`: cyan-to-gold completion fill.
- `data-size="sm"` or `data-size="lg"`: compact or large display sizes.

## Accessibility

Keep `aria-valuenow`, `aria-valuemin`, and `aria-valuemax` synchronized with `--stellartide-progress-scale`. Use a visible label when the progress value is important to the user.
