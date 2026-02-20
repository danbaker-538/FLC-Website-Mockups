# FLC Website Mockups Project

## Project Overview
Creating 2-3 website design mockups for **Fun Loving Company (FLC)**, a pre-seed biotech startup, to present to the founders as different creative directions.

## About the Company

**Fun Loving Company** is developing a natural alcohol alternative called **"Misdemeanor"**.

**Founders:**
- Jonathan Lu (Stanford GSB '17)
- Ronan Levy (founder of Fieldtrip Health, psychedelic therapy company)

**Product:** Misdemeanor - a proprietary blend containing:
- Kanna (South African herb, serotonin reuptake inhibitor)
- Cacao Extract
- Licorice Root

**Product Formats:**
- Social Shot (1oz / 29ml liquid bottle) — $7.50
- Fun Loving Gummies (canister) — $19.50

**Key Product Facts:**
- All ingredients are FDA GRAS (Generally Recognized as Safe)
- Effects last ~2 hours
- Creates relaxation, enhanced sociability, mild euphoria
- No hangover, no toxicity, no sleep disruption
- Commercial launch planned for 2026

**The Problem They Solve:**
- Alcohol consumption at lowest since Prohibition
- Americans increasingly disconnected (57% decline in time with friends)
- Existing alternatives fall short (cannabis unpredictable, mocktails have no effect)
- Gap in market for legal, safe, prosocial substance

## Target Audience
- B2C
- Primarily 30+ individuals
- Health-conscious but still want to have fun
- People who don't drink alcohol

## Brand Guidelines

**Colors:**
- Primary Orange: #E8724A
- Blue accent: #29ABE2
- Off-white background: #F9F9F9
- Dark text: #1A1A2E

**Typography:** Playfair Display (serif headings) + Inter (body text)

**Tone:** Fun, playful, slightly cheeky ("This much fun should be criminal. But it's not.")
- Lead with fun and experience, not health benefits
- Never preachy or clinical
- Words to use: feel good, loosen up, social magic, connection, good times, no regrets, Kanna, fast-acting, guilt-free
- Words to avoid: drug, substance, supplement, intoxicant, sober, wellness, detox, clinical

**Logo:** Hand-drawn style "Fun Loving Co." with orange underline accent — `assets/logo.webp`
- Always appear with orange underline, never alter or recolor

**Product Copy:**
- Social Shot: "Our smooth, great-tasting 1oz liquid shot packs a sweet Kanna-infused punch into one delicious hit — fast-acting and keeping you in your social sweet spot for up to 2 hours. No hangover. No regrets."
- Gummies: "Pop a few, feel the vibe shift. Our chewy, sweet Kanna-infused gummies pack the same great hit in a fun, grab-and-go format — fast-acting and keeping you in your social sweet spot for up to 2 hours. No hangover. No regrets."

## Design Inspiration
- Psilly Goose website (https://drinkpsillygoose.com/)
  - Gradient backgrounds (warm orange/pink/yellow)
  - Floating product shots
  - Scrolling benefit badges
  - Learn section with ingredient education
  - Community signup section

## Current Mockups

### mockup-1-bold-editorial.html ⭐ (Primary / Active)
- **This is the main mockup being developed**
- Balanced blue/orange/off-white color palette
- Hero with dual products (Social Shot + Gummies) side-by-side with hover enlarge/shrink interaction
  - Hero gummy image: `assets/gummies-hero.png` (open-lid can, scaled to 320px)
  - Hero shot image: `assets/social-shot.png`
- GSAP-powered entrance animations (elastic pop-in, swirl draw, text slide)
- Mouse parallax on hero products
- Continuous floating idle animation
- "GET LOOSE." wobble letter animation on hover (orange text)
- "STAY SHARP." in blue accent
- Segmented LED "vibe meter" bars (10 segments, blue empty / orange filled) with scroll-triggered staggered animation
- Glassmorphic 3D-tilt learn cards with blue top border
- Warm gradient color washes throughout sections (peach-to-blue)
- SVG grain/noise texture overlay
- Benefits ticker on blue background
- Newsletter section on blue background
- Scroll-triggered fade-in animations via IntersectionObserver
- Active nav link highlighting on scroll
- Navbar background change on scroll
- Shop section with both Social Shot ($7.50) and Gummies ($19.50)
  - Shop gummy image: `assets/gummy-product-new.png` (closed jar)
  - Shop shot image: `assets/bottle.webp`
- **"The Vibe" gallery** — auto-scrolling carousel of 7 marketing ads (excludes 3253293.jpg), pauses on hover
- **Enhanced vibe meters** — light blue card background per meter, filled segments pulse with blue glow animation (`segmentGlow`)
- **Newsletter background** — "Socialize Unleashed" gummy ad (3253222.jpg) subtly overlaid behind the blue newsletter section
- Fonts: Playfair Display + Inter

### mockup-2-clean-premium.html
- Sophisticated, minimal, trustworthy
- Clean whitespace
- Trust metrics prominently displayed
- Step-by-step "How It Works" section
- Fonts: DM Serif Display + DM Sans

### mockup-3-playful-social.html
- Fun, community-focused, energetic
- Announcement bar
- Playful animations (wiggling bottle, floating badges)
- Strong newsletter/community focus
- Fonts: Fraunces + Plus Jakarta Sans

## Pages Needed
1. Homepage (included in all mockups)
2. News page
3. Learn tab (product showcase + Kanna explanation)

## Assets

### Product Images
- `assets/bottle.webp` — Original product bottle image (used in shop section for Social Shot)
- `assets/logo.webp` — Company logo (copied from FunLoving_new_lgoo_BlueRed.webp)
- `assets/social-shot.png` — Social Shot with liquid swirl, transparent background (used in hero)
- `assets/social-shot.jpg` — Social Shot with white background
- `assets/gummies.png` — Original gummy canister, transparent background (not currently used)
- `assets/gummies.jpg` — Original gummy canister with white background (not currently used)
- `assets/gummies-hero.png` — New open-lid gummy can, transparent background (used in hero, 320px)
- `assets/gummy-product-new.png` — New closed jar gummy product (used in shop section)
- `assets/gummy product.jpg` — New gummy product jpg (not currently used)
- `assets/gummy no back.png` — New gummy with transparent background (not currently used)
- `assets/cap.png` — Cropped bottle cap (not currently used)
- `assets/bottle-nocap.png` — Cropped capless bottle (not currently used)

### Marketing Materials (`marketing materials/` folder)
- `3253061.jpg` — "Unlock the Vibe" vertical gummy ad (in gallery)
- `3253184.mp4` — Video asset (unused)
- `3253222.jpg` — "Socialize Unleashed" vertical gummy ad (in gallery + newsletter bg in v2)
- `3253225.jpg` — "Pop a Gummy" vertical gummy ad (in gallery)
- `3253284.jpg` — "Your New Social Superpower" square shot ad (in gallery)
- `3253288.jpg` — "Unlock Your Social Sweet Spot" square shot infographic (in gallery)
- `3253292.jpg` — "Your New Social Sweet Spot" square shot ad with citrus — favorite (in gallery)
- `3253293.jpg` — "The Social Shot" square lifestyle ad — excluded from gallery
- `3253296.jpg` — "Find Your Social Sweet Spot" square shot ad (in gallery)
- `3253507.mp4` — Video asset (unused)

## Deployment
- **GitHub Pages:** https://danbaker-538.github.io/FLC-Website-Mockups/
- **Repo:** https://github.com/danbaker-538/FLC-Website-Mockups
- Deploys automatically on push to `main` via `.github/workflows/static.yml`
- `index.html` redirects to `mockup-1-bold-editorial.html`

## Reference Links
- Current company website: https://wearefunloving.com/
- Design inspiration: https://drinkpsillygoose.com/

## Competitors/Adjacent Products
- Feel Free (feelfreetonic.com)
- Brez (drinkbrez.com)
- Kin Euphorics (kineuphoric.com)
- Psilly Goose (drinkpsillygoose.com)
