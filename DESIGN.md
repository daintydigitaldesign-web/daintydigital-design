---
version: alpha
name: Dainty Digital Design
description: Gentle, organised printables and planners — warm minimalism that feels like a quiet morning.
colors:
  ink: "#3d3746"
  ink-soft: "#635d6e"
  ink-muted: "#8d8696"
  accent: "#b8889e"
  accent-deep: "#a07086"
  accent-soft: "#d4b8c4"
  paper: "#fdfaf6"
  paper-warm: "#faf5ef"
  card: "rgba(255, 255, 255, 0.85)"
  card-solid: "#ffffff"
  line: "rgba(190, 175, 185, 0.35)"
  line-strong: "rgba(160, 140, 150, 0.5)"
  gold: "#c9a27e"
  gold-soft: "#e0c9a8"
  shadow-soft: "rgba(61, 55, 70, 0.06)"
  shadow-medium: "rgba(61, 55, 70, 0.1)"
  shadow-strong: "rgba(61, 55, 70, 0.15)"
  glass-bg: "rgba(255, 255, 255, 0.72)"
  glass-border: "rgba(255, 255, 255, 0.5)"
  scrim: "rgba(61, 55, 70, 0.35)"
typography:
  display-1:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Helvetica Neue', 'Segoe UI', Roboto, sans-serif"
    fontSize: "clamp(2.5rem, 6vw, 4rem)"
    fontWeight: 600
    lineHeight: 1.05
    letterSpacing: "-0.03em"
    fontOpticalSizing: auto
  display-2:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Helvetica Neue', 'Segoe UI', Roboto, sans-serif"
    fontSize: "clamp(1.75rem, 4vw, 2.5rem)"
    fontWeight: 500
    lineHeight: 1.15
    letterSpacing: "-0.02em"
    fontOpticalSizing: auto
  display-3:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Helvetica Neue', 'Segoe UI', Roboto, sans-serif"
    fontSize: "clamp(1.375rem, 3vw, 1.75rem)"
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: "-0.015em"
    fontOpticalSizing: auto
  body-lg:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'Helvetica Neue', 'Segoe UI', Roboto, 'Ubuntu', sans-serif"
    fontSize: "1.125rem"
    lineHeight: 1.7
    letterSpacing: "-0.005em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'Helvetica Neue', 'Segoe UI', Roboto, 'Ubuntu', sans-serif"
    fontSize: "1rem"
    lineHeight: 1.7
  body-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'Helvetica Neue', 'Segoe UI', Roboto, 'Ubuntu', sans-serif"
    fontSize: "0.875rem"
    lineHeight: 1.6
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Helvetica Neue', 'Segoe UI', Roboto, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 600
    letterSpacing: "0.12em"
    textTransform: "uppercase"
  label-sm:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Display', 'Helvetica Neue', 'Segoe UI', Roboto, sans-serif"
    fontSize: "0.6875rem"
    fontWeight: 600
    letterSpacing: "0.1em"
    textTransform: "uppercase"
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, 'SF Pro Text', 'Helvetica Neue', 'Segoe UI', Roboto, 'Ubuntu', sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 500
    letterSpacing: "0.01em"
    lineHeight: 1
rounded:
  sm: "8px"
  md: "12px"
  lg: "16px"
  xl: "24px"
  full: "9999px"
spacing:
  "1": "4px"
  "2": "8px"
  "3": "12px"
  "4": "16px"
  "5": "20px"
  "6": "24px"
  "8": "32px"
  "10": "40px"
  "12": "48px"
  "16": "64px"
  "20": "80px"
  "24": "96px"
motion:
  spring-damping: 1
  spring-response: "0.4"
  spring-bounce-damping: 0.8
  spring-bounce-response: "0.35"
  transition-fast: "120ms cubic-bezier(0.2, 0, 0.38, 1)"
  transition-base: "200ms cubic-bezier(0.2, 0, 0.38, 1)"
  transition-slow: "320ms cubic-bezier(0.2, 0, 0.38, 1)"
  transition-spring: "cubic-bezier(0.2, 0.6, 0.3, 1.2)"
elevation:
  glass:
    backgroundColor: "{colors.glass-bg}"
    backdropFilter: "blur(24px) saturate(180%)"
    border: "1px solid {colors.glass-border}"
    borderRadius: "{rounded.lg}"
    boxShadow: "0 1px 2px {colors.shadow-soft}, 0 4px 12px {colors.shadow-medium}, inset 0 1px 0 rgba(255, 255, 255, 0.6)"
  glass-heavy:
    backgroundColor: "{colors.glass-bg}"
    backdropFilter: "blur(40px) saturate(200%)"
    border: "1px solid {colors.glass-border}"
    borderRadius: "{rounded.xl}"
    boxShadow: "0 2px 4px {colors.shadow-soft}, 0 12px 32px {colors.shadow-medium}, inset 0 1px 0 rgba(255, 255, 255, 0.7)"
  card:
    backgroundColor: "{colors.glass-bg}"
    backdropFilter: "blur(24px) saturate(180%)"
    border: "1px solid {colors.glass-border}"
    borderRadius: "{rounded.lg}"
    boxShadow: "0 1px 2px {colors.shadow-soft}, 0 4px 16px {colors.shadow-medium}, inset 0 1px 0 rgba(255, 255, 255, 0.5)"
components:
  btn-primary:
    backgroundColor: "{colors.accent}"
    textColor: "#ffffff"
    rounded: "{rounded.full}"
    padding: "12px 24px"
    typography: "{typography.button}"
    boxShadow: "0 1px 2px {colors.shadow-soft}, 0 4px 12px rgba(176, 128, 154, 0.35)"
  btn-primary-hover:
    backgroundColor: "{colors.accent-deep}"
    textColor: "#ffffff"
    boxShadow: "0 2px 4px {colors.shadow-soft}, 0 8px 20px rgba(176, 128, 154, 0.45)"
    transform: "translateY(-1px)"
  btn-secondary:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    padding: "12px 24px"
    typography: "{typography.button}"
    border: "1px solid {colors.line}"
    backdropFilter: "blur(24px) saturate(180%)"
  btn-secondary-hover:
    backgroundColor: "{colors.card-solid}"
    borderColor: "{colors.accent-soft}"
    boxShadow: "0 4px 16px {colors.shadow-medium}"
    transform: "translateY(-1px)"
  btn-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink-soft}"
    rounded: "{rounded.full}"
    padding: "8px 16px"
    typography: "{typography.button}"
  btn-ghost-hover:
    backgroundColor: "rgba(176, 128, 154, 0.1)"
    textColor: "{colors.accent-deep}"
  nav-logo:
    width: "36px"
    height: "36px"
    borderRadius: "{rounded.md}"
    background: "linear-gradient(135deg, {colors.accent}, {colors.accent-deep})"
    color: "#ffffff"
    boxShadow: "0 2px 8px rgba(176, 128, 154, 0.35)"
  product-icon:
    width: "56px"
    height: "56px"
    borderRadius: "{rounded.md}"
    fontSize: "24px"
  value-icon:
    width: "48px"
    height: "48px"
    borderRadius: "{rounded.md}"
    backgroundColor: "{colors.glass-bg}"
    backdropFilter: "blur(24px) saturate(180%)"
    border: "1px solid {colors.glass-border}"
    fontSize: "22px"
  social-link:
    width: "40px"
    height: "40px"
    borderRadius: "{rounded.full}"
    backgroundColor: "{colors.card}"
    border: "1px solid {colors.line}"
    color: "{colors.ink-soft}"
  social-link-hover:
    backgroundColor: "{colors.card-solid}"
    borderColor: "{colors.accent-soft}"
    color: "{colors.accent-deep}"
    transform: "translateY(-2px)"
  flourish:
    width: "48px"
    height: "1px"
    background: "linear-gradient(90deg, transparent, {colors.accent}, transparent)"
---

## Overview

Dainty Digital Design is a brand for gentle, organised printables and planners. The visual identity evokes a quiet morning — warm, unhurried, and intentionally crafted. Every design decision serves the principle that organisation should feel calming, not clinical. The palette draws from aged paper, dried rose petals, and warm gold; typography uses the platform's system fonts with optical sizing so text reads beautifully at every scale; glass morphism creates depth without heaviness. Motion is spring-based, interruptible, and respects `prefers-reduced-motion`.

## Colors

- **Ink ({colors.ink}):** Primary text, headlines. A deep warm charcoal with purple undertones — softer than pure black.
- **Ink Soft ({colors.ink-soft}):** Body copy, secondary text. Readable but gentle.
- **Ink Muted ({colors.ink-muted}):** Metadata, timestamps, footnotes. Recedes gracefully.
- **Accent ({colors.accent}):** Primary interaction color — buttons, links, focus rings. A warm rose-mauve.
- **Accent Deep ({colors.accent-deep}):** Hover/active states for accent. Slightly deeper for clear affordance.
- **Accent Soft ({colors.accent-soft}):** Subtle backgrounds, hover fills, decorative elements.
- **Paper ({colors.paper}):** Page background. Warm off-white with a hint of cream.
- **Paper Warm ({colors.paper-warm}):** Section backgrounds, footer. Slightly warmer for depth.
- **Card ({colors.card}) / Card Solid ({colors.card-solid}):** Glass surface and its opaque fallback.
- **Line ({colors.line}) / Line Strong ({colors.line-strong}):** Borders, dividers. Semi-transparent for glass harmony.
- **Gold ({colors.gold}) / Gold Soft ({colors.gold-soft}):** Brand labels, flourishes, decorative accents. Warm metallic highlight.
- **Glass BG ({colors.glass-bg}) / Glass Border ({colors.glass-border}):** Glass morphism surface tokens.
- **Shadows:** Layered depth system — soft (ambient), medium (raised), strong (modal/overlay).
- **Scrim ({colors.scrim}):** Modal backdrop, dimmed backgrounds.

All colors include dark-mode, reduced-transparency, and high-contrast overrides via CSS media queries (not shown in tokens — implemented in CSS).

## Typography

System font stack first (`-apple-system`, `BlinkMacSystemFont`, `SF Pro`, `Segoe UI`, `Roboto`, `Ubuntu`, `sans-serif`) — respects user's platform, ships optical sizing, tracking tables, and legibility tuning. Georgia/serif reserved for italic taglines only.

Tracking is size-specific: negative on display (`-0.03em` to `-0.015em`), near-zero on body (`-0.005em`), positive on labels (`+0.12em`). Leading tightens as size grows (1.05 on display-1, 1.7 on body). Weight carries hierarchy: 600 on display-1, 500 on display-2/3, 400 on body.

`font-optical-sizing: auto` enabled on display tokens so the browser applies the font's built-in optical size axis.

## Layout

4px baseline spacing scale (`--space-1` through `--space-24`). Section padding uses `--space-16` (64px) desktop, `--space-12` (48px) mobile. Container max-width 880px. Grid-based product cards with `minmax(260px, 1fr)`.

## Motion

Spring tokens replace duration-based transitions:
- Default UI: critically damped (`damping 1.0`, `response 0.4s`) — no overshoot, graceful settle.
- Momentum interactions: under-damped (`damping 0.8`, `response 0.35s`) — slight bounce only when gesture carried velocity.
- Transition curves: `cubic-bezier(0.2, 0, 0.38, 1)` for standard, `cubic-bezier(0.2, 0.6, 0.3, 1.2)` for spring feel.

`prefers-reduced-motion: reduce` disables all motion — instant cross-fades only. IntersectionObserver scroll reveals respect this.

## Elevation & Depth

Glass morphism via `backdrop-filter: blur() + saturate()` with semi-transparent backgrounds. Three weights:
- `glass` (24px blur): standard cards, badges, nav
- `glass-heavy` (40px blur): modals, hero badge, prominent surfaces
- `card` (24px blur + lighter shadow): product cards, policy sections

Never stack light translucent surfaces. Bigger surfaces = stronger blur + deeper shadow. `prefers-reduced-transparency: reduce` falls back to opaque card-solid.

## Shapes

Modest rounding: `sm` (8px) on small interactive, `md` (12px) on buttons/icons, `lg` (16px) on cards, `xl` (24px) on hero/illustrations, `full` (pill) on badges, buttons, avatars.

## Components

All component tokens reference color/typography/rounded tokens — single source of truth. Variants are siblings (e.g., `btn-primary-hover`), not nested.

- Buttons: Primary (accent), Secondary (glass), Ghost (transparent). All pill-shaped, spring hover/tap.
- Icons: Product icons (56px, gradient bg), Value icons (48px, glass), Nav logo (36px, gradient).
- Social links: 40px glass circles, hover lift + color shift.
- Flourish: 48px gradient rule for visual rhythm.

## Do's and Don'ts

- **Do** use token references (`{colors.accent}`) in components — keeps palette single-source.
- **Do** start with critically damped springs; add bounce only for momentum-driven interactions.
- **Do** respect `prefers-reduced-motion`, `prefers-reduced-transparency`, `prefers-contrast`.
- **Do** anchor interactions to their source (transform-origin on trigger).
- **Don't** introduce colors outside the palette — extend the palette first.
- **Don't** nest component variants (`btn-primary.hover` is wrong; `btn-primary-hover` is right).
- **Don't** use fixed pixel typography — all sizes use `clamp()` or `rem`.
- **Don't** stack glass on glass — legibility collapses.
- **Don't** use AI-generated imagery that doesn't match the actual product files (template-first mockups only).