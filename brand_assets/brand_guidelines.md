---
brand: Branflakes
tagline: Fuel Your Stack.
architecture: Component-driven, High-craft SaaS
aesthetic: Pixel-perfect minimal, structured, intent-driven.
---

# Branflakes: Design System & Brand Architecture

## 1. Core Visual Identity
Branflakes operates at the intersection of high-performance SaaS aesthetics and consumer tech. The UI must feel like a premium, enterprise-grade tool. Execution must be flawless: prioritize extreme spatial discipline, purposeful white space, and zero "AI generated" or generic bootstrap/tailwind defaults. Think Stripe-level polish meets playful tech-cereal conceptualism.

## 2. Brand Lockup & Iconography
- **The Mark:** A modernist, geometric "data-bowl" constructed from precise cyan and amber interlocking vectors.
- **The Wordmark:** `BRANFLAKES` — strictly rendered in a clean, all-caps geometric sans-serif (System Blue).
- **Lockup Rules:** The icon must be optically centered above the wordmark. Maintain strict padding constraints around the logo to preserve its presence.
- **Tagline:** "Fuel Your Stack." Set in a lighter, high-contrast weight directly below the wordmark.

## 3. Color Tokens (Strict Adherence)
Colors must be implemented as exact variables. Do not deviate or introduce unapproved palettes.
- `--color-primary-tech`: `#0A84FF` (System Blue - Actionable/Primary)
- `--color-accent-amber`: `#FF9500` (Cereal/Fuel - Highlight/Interactive)
- `--color-surface-base`: `#F2F2F7` (System Light - Clean background foundation)
- `--color-text-high`: `#1C1C1E` (Dark Dark - Primary typography, avoid absolute `#000000`)
- `--color-text-muted`: `#8E8E93` (Light Gray - Secondary/Tertiary hierarchy)

## 4. Typographic Hierarchy
Strict separation of display and utility typography is required.
- **Display/Headings:** Use a precision geometric sans (e.g., `Inter Tight`).
  - *Treatment:* Apply aggressive kerning (`tracking-tight` or `-0.03em`) on large display sizes (H1/H2) to create a dense, structural tech feel.
- **Body/Interface:** Use a highly legible, neutral sans (e.g., `Inter`, `System UI`).
  - *Treatment:* Prioritize readability with a generous line-height (`1.7` / `leading-relaxed`) for long-form content.

## 5. Motion & Texture (The "Vibe" Layer)
- **Compositing:** Integrate subtle, hardware-accelerated noise/grain overlays on base surfaces to reduce flat "digital sterility" and add premium depth.
- **Component Motion:** Implement CSS-only, staggered micro-interactions. Elements should reveal via subtle, easing-based fade-ups (`cubic-bezier(0.16, 1, 0.3, 1)`) on page load.
- **Structural Motifs:** Use abstract geometric fragments (stylized pixel grids or data points) sparingly as background structural elements to reinforce the "decentralized network" theme.