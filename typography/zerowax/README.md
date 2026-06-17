# Zerowax Display Font

Zerowax is the current display/campaign font candidate for the Stellartide Design System.

## Local Files

The repo intentionally does not publish the Zerowax font binaries. The downloaded
zip uses a free-for-personal-use license that does not allow public distribution
without written permission from the author.

For local experiments, place licensed font files here:

- `fonts/Zerowax.otf`
- `fonts/Zerowax.ttf`

The main token preview will fall back to Bungee when the local Zerowax file is
not present.

## Usage

Use Zerowax only for expressive display moments:

- campaign headers
- hero words
- gallery titles
- badges and poster-style moments

Do not use Zerowax for body copy, form controls, compact labels, dense navigation, or repeated product UI.

## License Status

The bundled EULA is the `1001Fonts Free For Personal Use License`.

- Personal use is allowed.
- Commercial use requires prior written permission from the author.
- Modification is not allowed without written permission.
- Format conversion is allowed as long as the font is not otherwise modified.
- App/web embedding is limited by the personal-use terms.

Treat this as an experimental/local design-system asset until a commercial license is confirmed. Do not commit or publish the font binaries without that permission.

## CSS

```css
@font-face {
  font-family: "Zerowax";
  src: url("./fonts/Zerowax.otf") format("opentype");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

:root {
  --font-special: "Zerowax", "Bungee", Impact, fantasy;
}
```
