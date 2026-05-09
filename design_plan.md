# Aneta Trousilová — Site Plan

## Subject
Aneta Trousilová ("Anet") — UGC (User-Generated Content) creator based in Czechia.
Also building a UGC community / workshops brand: **ugc starterpack**.

## Goal
Replace the current Canva microsite (anetugc.my.canva.site) with a professional
website that keeps the same palette and warm-editorial vibe but feels like a real
boutique-creator portfolio rather than a Canva template.

## Audience
- Czech & international brand managers / agencies looking to book UGC creators
- Aspiring creators interested in the *ugc starterpack* community and workshops
- Bilingual presence: CZ + EN toggle

## Brand palette (locked — extracted from current site)
| Token | Hex | Role |
|---|---|---|
| `--cream` | `#f4f1e8` | Primary background, soft surfaces |
| `--ink` | `#191919` | Primary text, dark sections |
| `--copper` | `#bd8f53` | Primary accent — CTAs, eyebrows, hairlines |
| `--rust` | `#9b4819` | Secondary accent — emphasis, hover, headlines |
| `--paper` | `#ffffff` | Pure white surfaces (sparingly) |

## Existing content (verbatim, do not invent)

### Hero copy
- "hi, my name is Anet!"
- "few words about me"

### Section labels
- CLIENTS
- MY WORK
- LEVELS
- CHECK OUT MY SOCIAL MEDIA FOR MORE EXAMPLES
- I look forward to our future collaboration!
- ugc starterpack — building UGC community and workshops

### Work categories
- BEAUTY
- FOOD
- FASHION
- EVENTS and STORES
- APPS

### Client list (35+ brands)
Costa Coffee · Garnier · Mixa · Bübchen · Franui · Wolt · Rekola · Next Bike ·
Havlíkova Apotéka · Snuggs · Skinners · Powerlogy · Sellpy · Venira · Gingles ·
UGO · Citroněk · Bob Sanil · Lepší Kuchyň · Šufan · Guláš · Tiskařík · Triby ·
Textilomanie · Baumax · Magu · Levels · Miles · Planto Besto · Regenix · Vera ·
Ruf Ruf · mBank · Orea Hotels · OC Nový Smíchov · Máj

### Contact
- Email: **anetatrousilovaugc@gmail.com**
- Instagram (personal): https://www.instagram.com/trousilova_aneta/
- Instagram (community): https://www.instagram.com/ugc.starterpack/
- TikTok: https://www.tiktok.com/@ugcaneta.trou
- YouTube: https://youtube.com/@anetatrousilova22

## TBD (need from user before launch)
- [TBD] Full bio paragraph (CZ + EN)
- [TBD] Hero portrait photo (high-res)
- [TBD] Selected work samples (videos/stills) per category
- [TBD] Pricing or "Levels" definition
- [TBD] Domain name + registrar
- [TBD] Newsletter or contact form preference
- [TBD] ugc starterpack details — is it a course, community, paid workshop, all?

## What's wrong with the current Canva site
- Looks like a template, not a brand
- No real navigation — single long scroll
- Type is generic Canva defaults, not editorial
- Client names listed as text, no logos or visual proof of work
- No clear CTA hierarchy ("book me" buried)
- Czech and English mix without explicit language toggle
- No SEO surface (Canva blocks indexing of microsites)

## Stack (locked)
Next.js 16 App Router · Tailwind v4 · TypeScript · pnpm · Turbopack · Vercel deploy
GitHub for source · `next/font` with `latin-ext` for Czech diacritics
