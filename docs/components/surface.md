# Campaign Surface Components

Campaign surfaces are the expressive shell layer for Stellartide brand and event moments. They use source artwork as decorative chrome while keeping headings, copy, actions, and accessible names as real HTML.

## Asset Review

| Source file | Component | Role | Notes |
| --- | --- | --- | --- |
| `h_beb5214721.e00d962e..png` | `stellartide-surface--dialog-split` | Split text panel | Best for a primary message with extra lower text placement below the divider. The single-slot `stellartide-surface--dialog` variant remains available for simpler copy. |
| `h_beb5214953.c2e86a99..png` | `stellartide-surface--wide` | Wide content panel | Best for grouped copy, gallery descriptions, or documentation examples. |
| `h_beb5211675.e85ee004..png` | `stellartide-surface--hero` | Hero banner shell | Best for first-screen campaign moments with one compact message and action. |
| `h_beb5214715.6158de94..png` | `stellartide-surface--ribbon` | Compact label ribbon | Best for section labels, active banners, and short announcements. |
| `h_beb5214630.7006912d..png` | `stellartide-surface--micro` | Small status panel | Best for short stats, tags, and compact dashboard callouts. |
| `h_beb5214739.99c60426..png` | `stellartide-surface--icon-tile` | Icon tile shell | Best for small action tiles or feature shortcuts with a real accessible label nearby. |
| `main_kv_a_line_b.303d94cc..png` | `stellartide-surface-deco--gold-burst` | Decorative burst | Use behind or around content, never as the only information carrier. |
| `main_kv_a_line_a.031b2ede..png` | `stellartide-surface-deco--prism-burst` | Decorative prism burst | Use for larger campaign backdrops and edge energy. |
| `d_line_h.fe9d5c6c..png` | `stellartide-surface-deco--lightning-frame` | Decorative frame rays | Use as an oversized scene frame or motion backdrop. |
| `d_ms_fire.1edb4d12..png` | parked | Animated fire strip | Kept in assets for later, not part of the active preview. |
| `loading_ring.23d33386..png` | parked | Animated loading sigil | Kept in assets for later, not part of the active preview. |

## Source Boundaries

These component assets come from the local reference pool listed in the repo. They are useful for internal design-system exploration and implementation review. Replace them with owned or properly licensed Stellartide artwork before public product shipment.

## Usage

```html
<link rel="stylesheet" href="../../components/surface/surface.css" />

<section class="stellartide-surface stellartide-surface--dialog-split">
  <div class="stellartide-surface__content">
    <div class="stellartide-surface__main">
      <p class="stellartide-surface__eyebrow">Event live</p>
      <h2 class="stellartide-surface__title">Signal Found</h2>
      <p class="stellartide-surface__body">Keep the artwork decorative and the message as real text.</p>
    </div>
    <div class="stellartide-surface__footer">
      <span>Reward window</span>
      <strong>12 days</strong>
    </div>
  </div>
</section>

<span class="stellartide-surface-deco stellartide-surface-deco--gold-burst" aria-hidden="true"></span>

```

## Class Map

- `stellartide-surface`: base content shell with the asset on `::before`.
- `stellartide-surface__content`: real content layer above the artwork.
- `stellartide-surface__main`: primary content area for split panels.
- `stellartide-surface__footer`: lower split-panel text band.
- `stellartide-surface__eyebrow`, `stellartide-surface__title`, `stellartide-surface__body`, `stellartide-surface__actions`: optional content slots.
- `stellartide-surface-deco`: decorative non-content artwork layer.

## Motion

- Hover and pressed states are available when `stellartide-surface` is used on an `a` or `button`.
- Demo states can be forced with `data-state="hover"`, `data-state="pressed"`, `data-state="focus"`, or `data-state="disabled"`.
- `prefers-reduced-motion: reduce` disables surface transitions.
