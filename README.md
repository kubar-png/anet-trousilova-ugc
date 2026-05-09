# Anet Trousilová — UGC Creator

Personal website for Aneta Trousilová (UGC creator). Iteration-stage HTML mockups; Next.js scaffold to follow once a hero direction is locked.

## Live preview routes

| Route | Variant |
|---|---|
| `/` | Centered hero — slide-in cards, brick spotlight (current main direction) |
| `/mockups/index-green.html` | Left-text + right snap-scroll reels column |
| `/mockups/index.html` | Cream + terra (no green accent) |
| `/palette.html` | Green palette picker — click "Pick this" to copy hex |

## Files

- `index.html` — root copy of the centered hero variant
- `palette.html` — root copy of the green palette picker
- `design_plan.md` — discovery notes, brand list, contact, palette tokens
- `mockups/` — full set of variants + `archive-round-01/02/` for history

## Stack (planned)

Next.js App Router · Tailwind v4 · TypeScript · Vercel · GitHub. Current iteration is pure HTML/CSS/JS — fonts via Google Fonts CDN, all styles inline per file.

## Color tokens (locked)

- Cream `#f4f1e8` — primary background
- Ink `#1a1814` — primary text
- Brick `#9b4819` — warm emphasis
- Forest `#1a3326` — cool depth (British racing)

See `mockups/index-centered.html` `:root` for the full token system.
