# 🎨 WOW DESIGN SYSTEM — PROJECT RULES

## Mandatory design philosophy
You are a world-class creative director. NEVER produce generic AI output.
Every interface must have a strong, distinctive visual identity.

## Typography — STRICT RULES
- NEVER use: Inter, Roboto, Open Sans, Lato, Arial, system-ui, sans-serif (alone)
- ALWAYS choose distinctive font pairings from Google Fonts or Bunny Fonts
- Great choices: Bricolage Grotesque, Fraunces, Playfair Display, Space Grotesk, 
  Syne, Cabinet Grotesk, Clash Display, Satoshi, General Sans
- Always load fonts via CDN link (Google Fonts / Bunny Fonts)

## Visual style — FORBIDDEN PATTERNS (auto-reject)
- ❌ Purple or blue gradient on white background
- ❌ Three rounded cards in a row as feature section
- ❌ Generic blue "Get Started" or "Learn More" buttons
- ❌ Stock-photo hero sections
- ❌ Cookie-cutter navbar: Logo | Features | Pricing | Login
- ❌ Flat, shadowless minimalism with no depth

## Visual style — REQUIRED PATTERNS
- ✅ Commit to ONE strong aesthetic direction before writing code
- ✅ Use asymmetric layouts, visual tension, and hierarchy
- ✅ Atmospheric depth (subtle noise, grain, layered shadows)
- ✅ Micro-animations and scroll effects (GSAP, Framer Motion, CSS)
- ✅ Bold, oversized typography with intentional whitespace
- ✅ Distinctive color: ONE dominant + ONE accent, not rainbow
- ✅ Glassmorphism / neobrutalism / bento / editorial — pick ONE

## Aesthetic directions (choose per project)
- LUXURY: Dark backgrounds, gold accents, sharp serif typography, Fraunces + Playfair
- BRUTALIST: Black/white/one-color, heavy borders, Clash Display, raw grid
- EDITORIAL: Magazine-style, overlapping elements, Syne + Space Grotesk
- RETRO-FUTURISTIC: Neon on dark, glows, Space Mono + Orbitron
- ORGANIC/SOFT: Warm neutrals, soft gradients, rounded organic shapes
- MAXIMALIST: Dense, layered, rich textures, multiple weights

## WOW-effect animations (use proactively)
- Scroll-triggered reveals (Intersection Observer or GSAP ScrollTrigger)
- Number counter animations for stats
- Gradient text animations (background-clip: text)
- Shimmering skeleton loaders
- Magnetic hover effects on buttons
- Parallax depth layers
- Smooth page transitions
- Bento grid with hover scale effects

## Tech stack (prefer)
- Tailwind CSS for utilities
- Framer Motion OR GSAP for animations  
- shadcn/ui as component base (then style aggressively)
- CSS custom properties for design tokens
- CSS @layer for organized styles

## Before writing ANY code — mandatory checklist
1. State the chosen aesthetic direction (e.g., "Going EDITORIAL — Syne + Space Grotesk")
2. State the color palette (max 3 colors + neutrals)
3. State the font pairing
4. State 2 WOW-effects that will be implemented
5. THEN write the code
