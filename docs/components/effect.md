# Effect & VFX Components

Effect components are decorative animated accents for campaign moments. VFX components are composable scene layers built from supplied production artwork. They are not controls and should not carry essential information.

## Variants

- `stellartide-effect--level-flame`: cyan flame on a hot yellow field.
- `stellartide-effect--share-flame`: cyan/yellow flame on a green field.

## VFX Layers

- `stellartide-vfx--aurora-wash`: soft color field for campaign atmosphere.
- `stellartide-vfx--lightning-surge`: yellow energy wave that pulses across the lower scene.
- `stellartide-vfx--gold-rays`: angular gold rays for top/edge emphasis.
- `stellartide-vfx--prism-strike`: magenta and orange strike shards.
- `stellartide-vfx--impact-flash`: yellow impact mask for quick burst moments.
- `stellartide-vfx--fire-transition`: cyan and orange sprite-sheet fire wipe for scene transitions.
- `stellartide-vfx--loading-heat-field`: full-scene orange loading texture for warm backdrops.
- `stellartide-vfx--diagonal-lines`: pale diagonal speed-line plate for light or loading scenes.
- `stellartide-vfx--triangle-burst`: small triangular corner flourish for end-state or reward beats.
- `stellartide-vfx--cyan-fire-sprite`: 12-frame cyan flame sprite sheet.
- `stellartide-vfx--ember-transition`: 6-frame orange/magenta ember transition sheet.
- `stellartide-vfx--smoke-mask`: grayscale texture mask for smoke, grit, and transition overlays.

## Source Files

- Level flame GIF: [`components/effect/assets/effect-flame-level.gif`](../../components/effect/assets/effect-flame-level.gif)
- Share flame GIF: [`components/effect/assets/effect-flame-share.gif`](../../components/effect/assets/effect-flame-share.gif)
- Aurora wash: [`components/effect/assets/vfx-aurora-wash.png`](../../components/effect/assets/vfx-aurora-wash.png)
- Lightning surge: [`components/effect/assets/vfx-lightning-surge.png`](../../components/effect/assets/vfx-lightning-surge.png)
- Gold rays: [`components/effect/assets/vfx-gold-rays.png`](../../components/effect/assets/vfx-gold-rays.png)
- Prism strike: [`components/effect/assets/vfx-prism-strike.png`](../../components/effect/assets/vfx-prism-strike.png)
- Impact flash: [`components/effect/assets/vfx-impact-flash.png`](../../components/effect/assets/vfx-impact-flash.png)
- Fire transition: [`components/effect/assets/vfx-fire-transition-sheet.png`](../../components/effect/assets/vfx-fire-transition-sheet.png)
- Loading heat field: [`components/effect/assets/vfx-loading-heat-bg.png`](../../components/effect/assets/vfx-loading-heat-bg.png)
- Diagonal lines: [`components/effect/assets/vfx-diagonal-lines.png`](../../components/effect/assets/vfx-diagonal-lines.png)
- Triangle burst: [`components/effect/assets/vfx-triangle-burst.png`](../../components/effect/assets/vfx-triangle-burst.png)
- Cyan fire sprite: [`components/effect/assets/vfx-cyan-fire-sprites.png`](../../components/effect/assets/vfx-cyan-fire-sprites.png)
- Ember transition: [`components/effect/assets/vfx-ember-transition-sheet.png`](../../components/effect/assets/vfx-ember-transition-sheet.png)
- Smoke mask: [`components/effect/assets/vfx-smoke-mask.png`](../../components/effect/assets/vfx-smoke-mask.png)
- CSS implementation: [`components/effect/effect.css`](../../components/effect/effect.css)

## Usage

```html
<link rel="stylesheet" href="../../components/effect/effect.css" />

<span class="stellartide-effect stellartide-effect--level-flame" aria-hidden="true"></span>
<span class="stellartide-effect stellartide-effect--share-flame" aria-hidden="true"></span>

<div class="stellartide-vfx-scene" data-preset="strike" aria-hidden="true">
  <span class="stellartide-vfx stellartide-vfx--aurora-wash"></span>
  <span class="stellartide-vfx stellartide-vfx--smoke-mask"></span>
  <span class="stellartide-vfx stellartide-vfx--prism-strike"></span>
  <span class="stellartide-vfx stellartide-vfx--gold-rays"></span>
  <span class="stellartide-vfx stellartide-vfx--lightning-surge"></span>
  <span class="stellartide-vfx stellartide-vfx--impact-flash"></span>
  <span class="stellartide-vfx stellartide-vfx--fire-transition"></span>
</div>

<div class="stellartide-vfx-scene" data-preset="loading-burn" aria-hidden="true">
  <span class="stellartide-vfx stellartide-vfx--loading-heat-field"></span>
  <span class="stellartide-vfx stellartide-vfx--diagonal-lines"></span>
  <span class="stellartide-vfx stellartide-vfx--cyan-fire-sprite"></span>
  <span class="stellartide-vfx stellartide-vfx--ember-transition"></span>
  <span class="stellartide-vfx stellartide-vfx--triangle-burst"></span>
</div>
```

## Motion

- VFX layers animate with CSS keyframes and can be paused with `data-motion="paused"` or `.is-paused`.
- `prefers-reduced-motion: reduce` disables animation and keeps static layers visible.
- Use `--stellartide-vfx-scene-width` and `--stellartide-vfx-scene-height` to size preview containers.

## Accessibility

Use effects as decorative accents with `aria-hidden="true"`. If an effect represents a real status, pair it with nearby visible text and an accessible name.
