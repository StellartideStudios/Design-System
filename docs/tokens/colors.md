# Color Tokens

This is the first resolved color pass for the Stellartide design system.

## Asset Context

- Website asset pool: `C:\Users\ctrca\Downloads\hoyoverse_event_assets\downloaders\downloaded_assets\images`

## Background

- **Warm Cream Background:** `#FFF3DF`

## Core Palette

| Name | Hex | RGB | Primary use |
| --- | --- | --- | --- |
| Black | `#000000` | `0, 0, 0` | Hard contrast, dark surfaces, dark text |
| Racing Red | `#F20222` | `242, 2, 34` | Primary action, campaign heat, danger-adjacent energy |
| Atomic Tangerine | `#FF7433` | `255, 116, 51` | Secondary heat, hover states, graphic edges |
| Orange | `#FBA934` | `251, 169, 52` | Warning, highlights, celebration accents |
| Deep Purple | `#65005E` | `101, 0, 94` | Brand depth, dramatic panels, expressive dark surfaces |
| Indigo | `#490681` | `73, 6, 129` | Secondary depth, overlays, dark-mode contrast |
| Tropical Mint | `#61EFAF` | `97, 239, 175` | Success, secondary glow, support graphics |
| Aquamarine | `#31F5D3` | `49, 245, 211` | Focus, selection, electric outlines, active badges |

## Contrast Notes

Against `#FFF3DF`:

| Color | Contrast | Guidance |
| --- | ---: | --- |
| Black | 19.14:1 | Safe for normal text |
| Racing Red | 3.98:1 | Use for large text, icons, fills, or with a darker companion |
| Atomic Tangerine | 2.45:1 | Use decoratively or with dark text on top |
| Orange | 1.77:1 | Use decoratively or with dark text on top |
| Deep Purple | 11.16:1 | Safe for normal text |
| Indigo | 11.77:1 | Safe for normal text |
| Tropical Mint | 1.32:1 | Use decoratively or on dark surfaces |
| Aquamarine | 1.26:1 | Use decoratively or on dark surfaces |

## Semantic Roles

### Light Theme

| Role | Token | Value | Guidance |
| --- | --- | --- | --- |
| Page background | `color.background.canvas` | `#FFF3DF` | Default website and app background |
| Primary text | `color.text.primary` | `#000000` | Main readable text on warm cream |
| Brand text | `color.text.brand` | `#65005E` | Expressive headings or emphasized labels |
| Primary action background | `color.action.primary.background` | `#F20222` | Main CTA fill |
| Primary action text | `color.action.primary.text` | `#000000` | AA text on racing red |
| Secondary action background | `color.action.secondary.background` | `#31F5D3` | Electric alternate CTA fill |
| Secondary action text | `color.action.secondary.text` | `#000000` | AA text on aquamarine |
| Focus ring | `color.focus.ring` | `#31F5D3` | Focus indicator, especially on dark or black edges |
| Selection background | `color.selection.background` | `#65005E` | Selected states, active nav, tabs |
| Selection text | `color.selection.text` | `#FFF3DF` | AA text on deep purple |
| Warning background | `color.status.warning.background` | `#FBA934` | Warning fills and highlights |
| Warning text | `color.status.warning.text` | `#000000` | AA text on orange |
| Danger background | `color.status.danger.background` | `#F20222` | Destructive and urgent states |
| Danger text | `color.status.danger.text` | `#000000` | AA text on racing red |
| Success background | `color.status.success.background` | `#61EFAF` | Success fills and positive state marks |
| Success text | `color.status.success.text` | `#000000` | AA text on tropical mint |

### Dark Theme

| Role | Token | Value | Guidance |
| --- | --- | --- | --- |
| Page background | `color.background.canvas` | `#000000` | Default dark foundation |
| Expressive surface | `color.background.surface` | `#65005E` | Brand panels, dark cards, dramatic sections |
| Secondary surface | `color.background.surfaceMuted` | `#490681` | Secondary dark panels and overlays |
| Primary text | `color.text.primary` | `#FFF3DF` | Main readable text on black or purple |
| Primary action background | `color.action.primary.background` | `#31F5D3` | Main CTA fill on dark surfaces |
| Primary action text | `color.action.primary.text` | `#000000` | AA text on aquamarine |
| Hot accent | `color.accent.hot` | `#F20222` | Active marks, badges, graph edges |
| Warm accent | `color.accent.warm` | `#FBA934` | Highlights and celebratory marks |
| Focus ring | `color.focus.ring` | `#31F5D3` | High-visibility keyboard focus |

## Implementation Source

The machine-readable source lives at [`tokens/colors.json`](../../tokens/colors.json).

## Formats

### CSV

```text
000000,F20222,FF7433,FBA934,65005E,490681,61EFAF,31F5D3
```

### With #

```text
#000000, #F20222, #FF7433, #FBA934, #65005E, #490681, #61EFAF, #31F5D3
```

### Array

```json
["000000","F20222","FF7433","FBA934","65005E","490681","61EFAF","31F5D3"]
```

### Object

```json
{"Black":"000000","Racing Red":"F20222","Atomic Tangerine":"FF7433","Orange":"FBA934","Deep Purple":"65005E","Indigo":"490681","Tropical Mint":"61EFAF","Aquamarine":"31F5D3"}
```

### Extended Array

```json
[{"name":"Black","hex":"000000","rgb":[0,0,0],"cmyk":[0,0,0,100],"hsb":[0,0,0],"hsl":[0,0,0],"lab":[0,0,0]},{"name":"Racing Red","hex":"F20222","rgb":[242,2,34],"cmyk":[0,99,86,5],"hsb":[352,99,95],"hsl":[352,98,48],"lab":[51,77,53]},{"name":"Atomic Tangerine","hex":"FF7433","rgb":[255,116,51],"cmyk":[0,55,80,0],"hsb":[19,80,100],"hsl":[19,100,60],"lab":[65,49,59]},{"name":"Orange","hex":"FBA934","rgb":[251,169,52],"cmyk":[0,33,79,2],"hsb":[35,79,98],"hsl":[35,96,59],"lab":[76,21,68]},{"name":"Deep Purple","hex":"65005E","rgb":[101,0,94],"cmyk":[0,100,7,60],"hsb":[304,100,40],"hsl":[304,100,20],"lab":[22,49,-27]},{"name":"Indigo","hex":"490681","rgb":[73,6,129],"cmyk":[43,95,0,49],"hsb":[273,95,51],"hsl":[273,91,26],"lab":[21,50,-53]},{"name":"Tropical Mint","hex":"61EFAF","rgb":[97,239,175],"cmyk":[59,0,27,6],"hsb":[153,59,94],"hsl":[153,82,66],"lab":[86,-53,20]},{"name":"Aquamarine","hex":"31F5D3","rgb":[49,245,211],"cmyk":[80,0,14,4],"hsb":[170,80,96],"hsl":[170,91,58],"lab":[87,-54,3]}]
```

### XML

```xml
<palette>
  <color name="Black" hex="000000" r="0" g="0" b="0" />
  <color name="Racing Red" hex="F20222" r="242" g="2" b="34" />
  <color name="Atomic Tangerine" hex="FF7433" r="255" g="116" b="51" />
  <color name="Orange" hex="FBA934" r="251" g="169" b="52" />
  <color name="Deep Purple" hex="65005E" r="101" g="0" b="94" />
  <color name="Indigo" hex="490681" r="73" g="6" b="129" />
  <color name="Tropical Mint" hex="61EFAF" r="97" g="239" b="175" />
  <color name="Aquamarine" hex="31F5D3" r="49" g="245" b="211" />
</palette>
```
