# CabinCast Pro — Logo & Brand Guide

## Brand colors

| Name | Hex | Use |
|---|---|---|
| Forest Teal | `#0a3d3f` | Primary brand color, text, dark backgrounds |
| Cream | `#fbf8f1` | Background, light surfaces |
| Brand Gold | `#c9a449` | Accent, italic "Pro" on light backgrounds |
| Bright Gold | `#e0b94d` | Accent on dark backgrounds, sun in mountains |
| Deep Forest | `#1e4d3a` | Mountain silhouette layers |
| Moss | `#4a7c59` | Tagline, supporting text |

## Files in this folder

### SVG files (scalable, use whenever possible)

| File | What it's for |
|---|---|
| `cabincastpro-logo-primary.svg` | Main logo — website header, business cards, email sigs |
| `cabincastpro-logo-primary-dark.svg` | Same logo on dark background — photos, dark websites |
| `cabincastpro-logo-stacked.svg` | Vertical version — Instagram posts, posters, narrow layouts |
| `cabincastpro-social-icon.svg` | Square icon — Facebook, X, Instagram profile |
| `cabincastpro-avatar-round.svg` | Circular crop — Slack, Discord, anything that crops circles |
| `cabincastpro-icon-only.svg` | Just the TV mark — favicons, small spaces |

### PNG files (use when SVG isn't supported)

Same names as the SVGs but `.png`. All exported at 3x resolution for retina/print:
- Primary logos: 1800×540px
- Stacked: 870×690px
- Social/avatar: 1080×1080px
- Icon only: 840×660px

### Favicons (for the website)

| File | Size | Where it goes |
|---|---|---|
| `favicon-32.png` | 32×32 | Browser tab icon |
| `favicon-64.png` | 64×64 | Higher-res browser tab |
| `favicon-180.png` | 180×180 | iPhone home screen, bookmark icon |

## Where to use each

**Website header** → primary SVG (light bg) or dark SVG (if header is dark)
**Email signature** → primary PNG (light bg) — most email clients prefer PNG
**Business cards** → primary SVG, scale as needed
**Instagram profile** → social icon SVG (or PNG if uploading)
**Facebook profile** → avatar round PNG
**Letterhead** → primary SVG centered top
**Favicon on cabincastpro.com** → favicon-32.png and favicon-180.png

## Don'ts

- Don't recolor the logo — use only the brand colors above
- Don't stretch or distort proportions
- Don't add drop shadows, glows, or effects
- Don't place the logo on busy photo backgrounds without the dark version's solid background
- Don't change the typeface
- Don't separate the TV icon from the wordmark in the primary lockup

## Adding the logo to your website

To use the logo on cabincastpro.com, replace the current "CabinCast Pro" text in the nav with:

```html
<a href="/" class="logo">
  <img src="/logo/cabincastpro-logo-primary.svg" alt="CabinCast Pro" height="40">
</a>
```

For the favicon, add to `<head>` of index.html:

```html
<link rel="icon" type="image/png" sizes="32x32" href="/logo/favicon-32.png">
<link rel="apple-touch-icon" sizes="180x180" href="/logo/favicon-180.png">
```
