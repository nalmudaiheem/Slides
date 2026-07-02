---
version: alpha
name: Tawuniya
description: A confident insurance-grade system built from Tawuniya's actual brand theme — a vivid violet (#6B47F5) as the single hero accent on a white canvas, deep navy-violet (#322A5E) and near-navy ink (#0E2841) carrying institutional weight, and a soft mint (#D5FCE8) reserved for confidence/positive moments. Typography runs one family end-to-end — Plus Jakarta Sans (a geometric-sans stand-in for the brand's unavailable custom "Tawuniya" face) — differentiated only by weight, exactly mirroring the source brand's single-family, weight-only type system. The layout grammar is drawn directly from Tawuniya's own template deck: numbered agenda sections, full-bleed section dividers, oversized quote slides, violet-node timelines, year-marker milestone roadmaps, radial mind-maps, and photo profile cards. The result reads as trustworthy and modern rather than stiff-corporate — violet does the work that navy usually does in insurance/finance decks.

colors:
  bg: "#FFFFFF"
  ink: "#0E2841"
  ink-soft: "rgba(14, 40, 65, 0.66)"
  ink-faint: "rgba(14, 40, 65, 0.42)"
  primary: "#6B47F5"
  primary-tint: "rgba(107, 71, 245, 0.07)"
  primary-border: "rgba(107, 71, 245, 0.22)"
  lavender: "#D6D1ED"
  deep: "#322A5E"
  mint: "#D5FCE8"
  mint-ink: "#0F5C42"
  coral: "#FF6365"
  coral-soft: "#FFA9A2"
  surface: "#F4F3FA"
  positive: "#0F9D63"
  negative: "#FF6365"

typography:
  h1:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 800
    fontSize: "clamp(48px, 5.2vw, 104px)"
    lineHeight: 1.04
    letterSpacing: -0.02em
    color: "{colors.ink}"
  h2:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 700
    fontSize: "clamp(30px, 3.1vw, 56px)"
    lineHeight: 1.08
    letterSpacing: -0.015em
    color: "{colors.ink}"
  h3:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 600
    fontSize: "clamp(19px, 1.8vw, 28px)"
    lineHeight: 1.25
    color: "{colors.ink}"
  h4-eyebrow:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 700
    fontSize: "clamp(13px, 1.1vw, 15px)"
    lineHeight: 1
    letterSpacing: 0.1em
    textTransform: uppercase
    color: "{colors.primary}"
  body:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 400
    fontSize: "clamp(15px, 1.15vw, 19px)"
    lineHeight: 1.6
    color: "{colors.ink-soft}"
  agenda-num:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 800
    fontSize: "clamp(40px, 4vw, 72px)"
    lineHeight: 1
    letterSpacing: -0.01em
    color: "{colors.primary}"
  agenda-title:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 700
    fontSize: "clamp(19px, 1.7vw, 26px)"
    lineHeight: 1.2
    color: "{colors.ink}"
  agenda-sub:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 400
    fontSize: "clamp(13px, 1vw, 16px)"
    lineHeight: 1.4
    color: "{colors.ink-soft}"
  quote-text:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 600
    fontSize: "clamp(30px, 3vw, 52px)"
    lineHeight: 1.28
    letterSpacing: -0.01em
    color: "{colors.ink}"
  quote-mark:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 800
    fontSize: "180px"
    lineHeight: 0.5
    color: "{colors.primary}"
    opacity: 0.12
  step-num:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 700
    fontSize: "22px"
    lineHeight: 1
    color: "{colors.bg}"
  step-title:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 600
    fontSize: "clamp(15px, 1.3vw, 19px)"
    lineHeight: 1.25
    color: "{colors.ink}"
  milestone-year:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 800
    fontSize: "clamp(22px, 2vw, 32px)"
    lineHeight: 1
    color: "{colors.primary}"
  mindmap-center:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 800
    fontSize: "clamp(20px, 1.9vw, 28px)"
    lineHeight: 1.1
    color: "{colors.bg}"
  mindmap-node-title:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 700
    fontSize: "clamp(14px, 1.2vw, 17px)"
    lineHeight: 1.2
    color: "{colors.ink}"
  profile-name:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 800
    fontSize: "clamp(22px, 2vw, 30px)"
    lineHeight: 1.1
    color: "{colors.ink}"
  profile-role:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 500
    fontSize: "clamp(13px, 1vw, 16px)"
    lineHeight: 1.4
    color: "{colors.primary}"
  tag:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 600
    fontSize: 13px
    lineHeight: 1
    color: "{colors.primary}"
  meta:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 500
    fontSize: 13px
    lineHeight: 1.3
    letterSpacing: 0.03em
    color: "{colors.ink-faint}"
  cite:
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 600
    fontSize: 14px
    lineHeight: 1.3
    color: "{colors.ink-soft}"

spacing:
  pad-slide-x: "6.5vw"
  pad-slide-y: "6.5vh"
  gap-grid-lg: "3vw"
  gap-grid-md: "2vw"
  gap-grid-sm: "1.2vw"
  pad-card: "2.2rem 2rem"
  pad-card-sm: "1.4rem 1.5rem"
  pad-pill: "0.5rem 1.1rem"
  header-margin: "4vh"

canvas:
  width: 1920px
  height: 1080px
  background: "{colors.bg}"

radii:
  pill: "100px"
  card-lg: "24px"
  card-md: "18px"
  card-sm: "12px"
  circle: "50%"
  node: "16px"

components:
  card-tinted:
    background: "{colors.primary-tint}"
    border: "1.5px solid {colors.primary-border}"
    borderRadius: "18px"
    padding: "{spacing.pad-card}"
    description: "Primary content card. Violet-at-7% fill with a violet-at-22% 1.5px border. Universal soft-depth card used across agenda, highlight, and detail slides."
  card-mint:
    background: "{colors.mint}"
    color: "{colors.mint-ink}"
    borderRadius: "18px"
    padding: "{spacing.pad-card}"
    description: "Solid mint confidence card — used sparingly (max one per slide) for a positive/featured callout: a completed milestone, a key benefit, a trust statistic."
  tag-pill:
    background: "{colors.primary-tint}"
    color: "{colors.primary}"
    padding: "{spacing.pad-pill}"
    borderRadius: "{radii.pill}"
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 600
    fontSize: 13px
    description: "Soft violet-tint pill for section labels, category tags, and slide-header chrome."
  cta-button:
    background: "{colors.primary}"
    color: "{colors.bg}"
    padding: "1rem 2.4rem"
    borderRadius: "{radii.pill}"
    fontFamily: "'Plus Jakarta Sans', sans-serif"
    fontWeight: 700
    fontSize: 16px
    description: "Solid violet pill CTA with white text. The system's only fully-saturated fill outside of the deep-navy panels."
  nav-btn:
    width: 48px
    height: 48px
    borderRadius: "50%"
    border: "1.5px solid {colors.primary-border}"
    background: "{colors.bg}"
    color: "{colors.primary}"
    description: "Circular nav-arrow, hover inverts to solid violet fill with white icon."
  agenda-number:
    color: "{colors.primary}"
    description: "Oversized two-digit numeral (01, 02, 03...) in {typography.agenda-num}, positioned top-left of each agenda block, taken directly from the source deck's Agenda slide."
  section-divider-panel:
    background: "{colors.deep}"
    color: "{colors.bg}"
    description: "Full-bleed deep-navy-violet panel used for section-divider slides. Title in {typography.h1} rendered in white; a thin violet accent-line sits above the title."
  quote-glyph:
    color: "{colors.primary}"
    opacity: 0.12
    description: "Oversized quotation mark ({typography.quote-mark}) positioned behind/above the quote text on quote-class slides."
  step-node:
    width: 64px
    height: 64px
    borderRadius: "50%"
    background: "{colors.primary}"
    color: "{colors.bg}"
    description: "Circular numbered timeline node in solid violet with a white numeral. Completed steps use {colors.deep}; the current/active step uses {colors.mint} fill with {colors.mint-ink} numeral."
  step-connector:
    height: "3px"
    background: "{colors.lavender}"
    description: "Horizontal or vertical hairline connecting timeline step-nodes. Lavender by default; the completed segment (behind the active node) fills solid {colors.primary}."
  milestone-marker:
    width: 18px
    height: 18px
    borderRadius: "50%"
    background: "{colors.primary}"
    border: "4px solid {colors.primary-tint}"
    description: "Small violet dot with a soft violet halo ring, sitting on a horizontal milestone rail. The year label sits above, the description card below (or the reverse, alternating)."
  mindmap-center-node:
    background: "{colors.primary}"
    color: "{colors.bg}"
    borderRadius: "{radii.node}"
    description: "Central rounded-rect or circular node in solid violet holding the core topic, radiating connector lines to child nodes."
  mindmap-node:
    background: "{colors.lavender}"
    color: "{colors.ink}"
    borderRadius: "{radii.node}"
    padding: "{spacing.pad-card-sm}"
    description: "Child node in soft lavender fill, connected to the center node by a thin curved or angled {colors.lavender}-to-{colors.primary} line."
  profile-card:
    background: "{colors.bg}"
    border: "1.5px solid {colors.primary-border}"
    borderRadius: "{radii.card-lg}"
    description: "Photo (or photo-placeholder) on one side, name/role/contact block on the other. A thin violet rule separates photo from text block."
  closing-panel:
    background: "{colors.deep}"
    color: "{colors.bg}"
    description: "Deep-navy-violet full-bleed closing/thank-you surface with centered contact block and a soft radial violet glow behind the headline."
  progress-bar:
    position: "fixed bottom 0 left 0"
    height: "4px"
    background: "{colors.primary}"
    description: "Thin solid violet progress strip at the bottom edge of the viewport."
---

## Frontend Slides Fixed-Stage Policy

When this design system is used by the `frontend-slides` skill, generate the final deck as a **fixed 1920×1080 stage** that scales uniformly to the browser viewport. The deck should preserve a 16:9 slide canvas on every screen, including phones; it may letterbox or pillarbox, but it should not reflow slide content for mobile.

This policy has higher priority than any responsive behavior implied elsewhere in this file. Treat any `vw`/`vh`/`clamp()` values below as design proportions to translate into fixed 1920×1080 stage coordinates, not as live responsive rules in the generated deck.

Use `deck-stage.js` or an equivalent inline stage scaler for final output: render each slide at 1920×1080, scale the whole stage with one transform, and verify rendered screenshots for both text overflow and panel overlap.

## Provenance

This template is derived from Tawuniya's own PowerPoint theme (`clrScheme name="Tawuniya"` and `fontScheme name="Custom 1"` extracted directly from the brand deck's `theme1.xml`), not an invented palette. Two adaptations were made deliberately:

1. **Typeface substitution.** The source theme specifies a custom corporate face ("Tawuniya Medium" for headings, "Tawuniya" for body) that is not available as a web font — no files were embedded in the source file. `Plus Jakarta Sans` (Google Fonts, weights 300–800) was chosen as the closest open geometric-sans stand-in: similar x-height, similar geometric bowl construction, and — critically — enough weight range to run the *entire* system off one family, matching the brand's own single-family approach.
2. **No literal logo.** The source file contained only generic placeholder graphics ("COMPANY LOGO", "(icon)"), not Tawuniya's real logo or icon set. This template applies color, type, and layout only. Generated decks should leave an obvious, easily-swappable logo slot on title and closing slides (an empty top-left mark position) rather than fabricate a wordmark.

## Overview

Tawuniya is built around **one hero accent doing all the work a whole palette usually does**. The canvas is pure white (`{colors.bg}`). Headings and primary text sit in a near-navy ink (`{colors.ink}` — `#0E2841`) that reads as institutional and calm. Everything that needs to draw the eye — eyebrows, agenda numerals, CTAs, active timeline nodes, milestone markers, mind-map centers, quote glyphs — is the same saturated violet (`{colors.primary}` — `#6B47F5`). A deep navy-violet (`{colors.deep}` — `#322A5E`) is reserved for full-bleed "weight" surfaces: section dividers and the closing panel. A soft mint (`{colors.mint}` — `#D5FCE8`) is the system's *only* other fill color, and it is rationed deliberately — one mint card per slide, maximum — for genuinely positive or confidence-building moments (a completed step, a key benefit, a trust stat). Coral (`{colors.coral}` — `#FF6365`) exists in the palette but is not a decorative color; use it only for an actual attention/negative signal (a risk flag, a declined state), the same way `positive`/`negative` tokens work in other systems in this pack.

**Typography is a single family, weight-only.** Every text role — display headline, eyebrow, body, numerals, chrome — runs `Plus Jakarta Sans`. There is no second face anywhere in the system. Hierarchy is built entirely from weight (400 → 500 → 600 → 700 → 800), size, color, and letter-spacing. This mirrors the actual Tawuniya brand system (`majorFont` and `minorFont` in the source theme are both variants of the same "Tawuniya" family) and is the template's most distinctive trait relative to the rest of this pack, where most templates pair two type families.

**The layout grammar is not invented — it is the source deck's own slide vocabulary**, captured as reusable patterns: a numbered agenda, full-bleed section dividers, oversized quote slides (plain and with a photo/attribution), a violet-node step timeline, a year-marker milestone roadmap, a radial mind-map, a photo profile card, and a deep-navy thank-you/contact close. These eight patterns are the template's structural identity — reach for them first before inventing a new slide type.

**Key Characteristics:**
- Pure white canvas (`{colors.bg}`) everywhere except section-divider and closing surfaces, which flip to solid deep navy-violet (`{colors.deep}`).
- Violet (`{colors.primary}`) is the only accent used for interactive/emphasis chrome — eyebrows, numerals, CTAs, active nodes, tag pills, progress bar.
- Mint (`{colors.mint}`) is rationed to one confidence-callout per slide; never used as a background wash.
- One type family (`Plus Jakarta Sans`) for every role; hierarchy comes from weight and size, never a second face.
- Cards are soft violet tints (7% fill, 22%-opacity border, 18px radius) — no drop shadows, no opaque fills except CTAs, mint cards, and deep-navy panels.
- Eight named layout patterns carried directly from the brand deck: agenda, section-divider, quote, quote-with-photo, timeline, milestones, mind-map, profile-card, plus a thank-you close.

## Colors

### Palette

- **Bg** (`{colors.bg}` — `#FFFFFF`): Universal canvas for every content slide. Never off-white or cream — Tawuniya's ground is clinically white, reinforcing clarity and trust.
- **Ink** (`{colors.ink}` — `#0E2841`): Primary text and headline color. A deep desaturated navy, not black — softer than pure `#000` while still reading as authoritative.
- **Ink-soft** (`{colors.ink-soft}` — ink at 66%): Body paragraphs and secondary text.
- **Ink-faint** (`{colors.ink-faint}` — ink at 42%): Tertiary metadata — slide numbers, dates, captions.
- **Primary** (`{colors.primary}` — `#6B47F5`): The signature violet. The system's only accent color for chrome, numerals, CTAs, active states, and links. Taken directly from the brand's `accent1`.
- **Primary-tint** (`{colors.primary-tint}` — violet at 7%): Default card fill.
- **Primary-border** (`{colors.primary-border}` — violet at 22%): Default card and pill border.
- **Lavender** (`{colors.lavender}` — `#D6D1ED`): Soft secondary fill for mind-map child nodes and inactive timeline connectors. Brand `accent2`.
- **Deep** (`{colors.deep}` — `#322A5E`): Full-bleed panel color for section-dividers and the closing surface. Brand `accent4`.
- **Mint** (`{colors.mint}` — `#D5FCE8`): Rationed confidence accent — one card per slide, maximum. Brand `accent3`.
- **Mint-ink** (`{colors.mint-ink}` — `#0F5C42`): Text/icon color used on top of mint fills (mint itself is too light for body-text contrast).
- **Coral** / **coral-soft** (`#FF6365` / `#FFA9A2`): Reserved for genuine alert/negative moments only — never decorative. Brand `accent6` / `accent5`.
- **Surface** (`{colors.surface}` — `#F4F3FA`): Very light neutral wash, used only behind full-width table/chart zones that need to visually separate from the pure-white canvas without introducing a second hue.
- **Positive** / **Negative** (`#0F9D63` / `#FF6365`): Inline directional indicators only (deltas, up/down arrows) — same convention as other templates in this pack.

### Defaults

- **Default surface background**: `{colors.bg}` white, except section-divider and closing surfaces, which default to `{colors.deep}`.
- **Default headline color**: `{colors.ink}` — headlines are never violet. Violet is reserved for accent moments.
- **Default body text color**: `{colors.ink-soft}`.
- **Default eyebrow color**: `{colors.primary}`, always uppercase, always 0.1em tracked.
- **Default card fill**: `{colors.primary-tint}` (violet at 7%) with `{colors.primary-border}` (violet at 22%) 1.5px border.
- **Default numeral / metric color**: `{colors.primary}`.
- **Default CTA**: `{components.cta-button}` — solid violet pill, white text.
- **Mint usage cap**: at most one `{components.card-mint}` per slide. Mint is a confidence signal, not a palette color to reach for casually — overusing it flattens its meaning.

## Typography

### Font Family Stack

The system runs exactly one face: **Plus Jakarta Sans** (Google Fonts, weights 300–800), used for every heading, numeral, body paragraph, and piece of chrome. Weight is the only lever: 400 for body, 500–600 for sub-headings and labels, 700 for headlines and step titles, 800 for display numerals and the largest headline moments. There is no second family anywhere — do not introduce a serif or a monospace accent face; that would break the system's most defining trait.

### Typography Scale

| Token | Size | Weight | Use |
|---|---|---|---|
| `{typography.h1}` | 48–104px clamp | 800 | Cover title, section-divider title, closing headline |
| `{typography.h2}` | 30–56px clamp | 700 | Primary section headline on a content slide |
| `{typography.h3}` | 19–28px clamp | 600 | Sub-section / card title |
| `{typography.h4-eyebrow}` | 13–15px clamp | 700 | Uppercase eyebrow, always violet, 0.1em tracked |
| `{typography.body}` | 15–19px clamp | 400 | Standard paragraph |
| `{typography.agenda-num}` | 40–72px clamp | 800 | Big "01 / 02 / 03" agenda numeral |
| `{typography.agenda-title}` | 19–26px clamp | 700 | Agenda section title |
| `{typography.agenda-sub}` | 13–16px clamp | 400 | Agenda sub-bullet lines |
| `{typography.quote-text}` | 30–52px clamp | 600 | Big quote body |
| `{typography.quote-mark}` | 180px | 800 | Oversized decorative quotation glyph at 12% opacity |
| `{typography.step-num}` | 22px | 700 | Numeral inside a timeline step-node |
| `{typography.step-title}` | 15–19px clamp | 600 | Timeline step caption |
| `{typography.milestone-year}` | 22–32px clamp | 800 | Year label on a milestone marker |
| `{typography.mindmap-center}` | 20–28px clamp | 800 | Text inside the mind-map center node |
| `{typography.mindmap-node-title}` | 14–17px clamp | 700 | Mind-map child-node title |
| `{typography.profile-name}` | 22–30px clamp | 800 | Name on a profile card |
| `{typography.profile-role}` | 13–16px clamp | 500 | Role/title line on a profile card, in violet |
| `{typography.tag}` | 13px | 600 | Tag-pill label |
| `{typography.meta}` | 13px | 500 | Slide-counter / date meta |
| `{typography.cite}` | 14px | 600 | Attribution line under a quote |

### Defaults

- **Default cover/divider/closing size**: `{typography.h1}`, weight 800, -0.02em tracking, always in `{colors.ink}` on white surfaces or `{colors.bg}` white on `{colors.deep}` surfaces.
- **Default content headline**: `{typography.h2}`, weight 700.
- **Default body**: `{typography.body}`, weight 400, in `{colors.ink-soft}`, line-height 1.6.
- **Default eyebrow**: `{typography.h4-eyebrow}`, weight 700, violet, uppercase, 0.1em tracking. Never skip the eyebrow on a content slide — it is the system's structural signature in place of a second type family.
- **Weight ladder**: 400 (body) → 500 (secondary labels, profile role) → 600 (sub-heads, quote text, cite) → 700 (h2, h3, eyebrow, agenda title, step title) → 800 (h1, agenda numeral, milestone year, mind-map center). Don't skip rungs; the ladder is what replaces a second font in creating hierarchy.

### Typography Principles

Because there is only one family, **every hierarchy decision is made with weight, size, color, and tracking** — never with a different face. Eyebrows are the primary "this is a label, not a headline" signal (uppercase + 0.1em tracking + violet + weight 700); without all four attributes together, a small violet line reads as a stray accent, not a structural eyebrow. Numerals (agenda numbers, milestone years, step-node digits) are always weight 700–800 in violet — they are the system's numerical accent moment, equivalent to how other templates in this pack reserve a single accent color for metrics.

## Layout

### Canvas System

Slides are authored at the fixed 1920×1080 stage per the Fixed-Stage Policy above. Default slide padding is `{spacing.pad-slide-x}` (6.5vw translated to ~125px at 1920 width) left/right and `{spacing.pad-slide-y}` top/bottom, leaving room for the persistent bottom chrome (progress bar, nav buttons, slide meta).

### Content Grids — The Eight Layout Patterns

These are captured directly from Tawuniya's own template deck and are this template's layout grammar. Reach for the matching pattern before inventing a new one:

1. **Agenda** — A grid of numbered blocks (`{components.agenda-number}` + `{typography.agenda-title}` + 2–3 `{typography.agenda-sub}` lines), 2–3 columns depending on section count. Numerals are always two-digit (`01`, `02`...) in violet weight 800.
2. **Section Divider** — Full-bleed `{components.section-divider-panel}` (solid `{colors.deep}`). A single `{typography.h1}` title in white, optionally preceded by a small violet eyebrow. No body copy, no cards — this slide is a breath, not a content moment.
3. **Quote** — Centered `{typography.quote-text}` with an oversized `{components.quote-glyph}` positioned behind/above it. Plain variant has no attribution; the "quote with photo" variant adds a circular photo, name, and job title beneath the quote, left- or right-aligned against the quote block.
4. **Timeline / Steps** — A horizontal (or vertical, for long sequences) row of `{components.step-node}` circles connected by `{components.step-connector}` lines. Completed steps fill `{colors.deep}`, the active step fills `{colors.mint}` with `{colors.mint-ink}` numeral, future steps fill `{colors.primary}` at reduced opacity (0.9 → 0.7 → 0.5 as steps move further into the future). Step titles sit below each node.
5. **Milestones / Roadmap** — A horizontal rail with `{components.milestone-marker}` dots at year intervals (the source deck uses 2025–2029). Year label and description card alternate above/below the rail to avoid crowding.
6. **Mind Map** — A radial layout: one `{components.mindmap-center-node}` (solid violet) with 4–8 `{components.mindmap-node}` children (lavender fill) connected by thin curved lines. Used for a single topic branching into related sub-themes, each sub-theme optionally expanding into 2–3 lines of supporting body text.
7. **Profile Card** — `{components.profile-card}`: photo (or photo-placeholder) on one side, `{typography.profile-name}` + `{typography.profile-role}` (violet) + contact meta (address/phone in `{typography.meta}`) on the other, separated by a thin violet rule.
8. **Thank You / Close** — `{components.closing-panel}` (solid `{colors.deep}`), centered "Thank you" or equivalent headline in white, a contact block (name, role, email) beneath in `{typography.body}` at reduced opacity, and a soft radial violet glow positioned behind the headline for atmosphere.

Standard content slides (not one of the eight named patterns) follow the same slide-header rhythm as the rest of this pack: an `{typography.h4-eyebrow}` top-left, an optional `{components.tag-pill}` top-right, a `{typography.h2}` section headline, and a flexible content region below (text, `{components.card-tinted}` grid, table, or chart).

### Padding and Gap Scale

| Token | Value | Use |
|---|---|---|
| `{spacing.pad-slide-x}` | 6.5vw | Slide left/right padding |
| `{spacing.pad-slide-y}` | 6.5vh | Slide top/bottom padding |
| `{spacing.gap-grid-lg}` | 3vw | Gap between agenda columns / mind-map branches |
| `{spacing.gap-grid-md}` | 2vw | Gap in standard 2–3 column content grids |
| `{spacing.gap-grid-sm}` | 1.2vw | Gap between timeline nodes / tight card rows |
| `{spacing.pad-card}` | 2.2rem 2rem | Standard card internal padding |
| `{spacing.pad-card-sm}` | 1.4rem 1.5rem | Compact card padding (mind-map nodes, mini stats) |
| `{spacing.header-margin}` | 4vh | Space below the slide-header before content begins |

### Persistent Chrome

- **Slide meta** bottom-left — `{typography.meta}`, current/total slide count.
- **Nav controls** bottom-right — two `{components.nav-btn}` circular arrows.
- **Progress bar** — `{components.progress-bar}`, a 4px solid violet strip at the bottom edge, width tracking deck position.

## Depth and Elevation

The system uses the same **soft-tint, no-shadow** depth language as the rest of this pack: cards are violet-at-7% fills with violet-at-22% 1.5px borders and 18px rounded corners — never a drop shadow. The only exceptions are the deep-navy section-divider/closing panels (which use flat solid color, no border, no shadow — the color shift itself signals a change in surface) and the mint confidence card (solid fill, no border, reserved for one genuinely positive moment per slide). CTAs get a single soft violet-tinted shadow on hover (`0 10px 28px rgba(107, 71, 245, 0.28)`) — the system's only shadow.

## Shapes and Treatment

- **Radii ladder**: `{radii.pill}` (100px, fully rounded — tags, CTAs, nav buttons) → `{radii.card-lg}` (24px — hero/profile cards) → `{radii.card-md}` (18px — standard content cards) → `{radii.card-sm}` (12px — mini cards, mind-map nodes) → `{radii.circle}` (50% — step-nodes, milestone dots, photo crops, nav buttons). No square (0px) corners anywhere except the progress bar and full-bleed panels.
- **Borders**: 1.5px `{colors.primary-border}` (violet at 22%) is the universal card/pill border weight. Never opaque violet borders on cards — that reads as a different, harsher system.
- **Connectors**: timeline and mind-map connector lines are always thin (2–3px), lavender by default, solid violet only for the "completed" segment.

## Do's and Don'ts

### Do
- Keep the canvas pure white for every content slide; reserve `{colors.deep}` solid panels for section-dividers and the closing slide only.
- Use `{colors.primary}` violet as the only interactive/emphasis accent — eyebrows, numerals, CTAs, active states, progress bar.
- Run every text role in Plus Jakarta Sans, differentiated only by weight. Never introduce a second family.
- Reach for the eight named layout patterns (agenda, divider, quote, quote-with-photo, timeline, milestones, mind-map, profile card, thank-you) before inventing a new slide type.
- Ration `{colors.mint}` to one confidence-callout card per slide, maximum.
- Leave an obvious, empty logo slot on title/closing slides rather than fabricating a Tawuniya wordmark.

### Don't
- Don't introduce a second type family — this system's identity depends on weight-only hierarchy.
- Don't use violet for headline text — headlines are `{colors.ink}`, violet is reserved for accent moments.
- Don't use drop shadows on cards; the depth language is tint + border only.
- Don't use `{colors.coral}` decoratively — it exists only for genuine alert/negative signals.
- Don't wash whole slide backgrounds in mint or lavender — those are card-level fills, not canvas colors.
- Don't fabricate a Tawuniya logo, wordmark, or icon set — none was present in the source file.

## Responsive Behavior

Sized with `clamp()` for type at generation time, then translated into fixed 1920×1080 stage coordinates per the Fixed-Stage Policy. The deck should letterbox/pillarbox on non-16:9 screens rather than reflow. Slide transitions: 450ms ease, opacity + 30px translateY. Nav buttons disable (40% opacity) at first/last slide. Keyboard (arrows/space/page up-down), touch swipe (50px threshold), and click nav are all supported per the shared `html-template.md` controller.

## Arabic / RTL Content

Tawuniya operates primarily in the Saudi market; a bilingual EN/AR build is a realistic and encouraged use of this template.

- **Recommended Arabic pairing**: `Almarai` (Google Fonts, weights 300/400/700/800) — a geometric Arabic sans designed for a Saudi financial brand, pairs naturally with Plus Jakarta Sans in x-height and weight range. Use it for every role Plus Jakarta Sans covers in the Latin build.
- **Direction**: set `dir="rtl"` on the document (or per-slide) for Arabic content; mirror the layout (eyebrow/tag-pill swap sides, agenda numerals move to the right edge, nav-button order reverses).
- **Line-height**: increase body line-height slightly (1.7–1.8 vs. 1.6) — Arabic script has taller ascenders/descenders than Latin.
- **Numerals**: keep agenda numbers, years, and step numerals in Western Arabic numerals (01, 02, 2025...) — this matches convention in Saudi corporate/financial decks even in full-Arabic builds.
- **Don't** rotate or mirror the violet quote-glyph or icon shapes — only text direction and text-adjacent layout (alignment, padding) should flip.

### Loading

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Almarai:wght@300;400;700;800&display=swap" rel="stylesheet">
```

## Iteration Guide

1. Every new slide starts on `{colors.bg}` white, unless it is a section-divider or closing slide, which start on `{colors.deep}`.
2. Every new standard content slide carries a slide-header: violet uppercase eyebrow top-left, optional `{components.tag-pill}` top-right, `{typography.h2}` headline below.
3. Every new numeral (agenda number, milestone year, step-node digit) is Plus Jakarta Sans weight 700–800 in violet.
4. Every new card defaults to `{components.card-tinted}` (violet-at-7% fill, violet-at-22% border, 18px radius) unless it is the slide's single mint confidence-callout.
5. If the content matches one of the eight named patterns, use that pattern's exact component set rather than approximating it with generic cards.
6. If a surface feels sparse, add more agenda items, more mind-map branches, or more timeline steps — don't add a second accent color to fill space.

## Known Gaps

- **The real "Tawuniya" typeface is not used.** Plus Jakarta Sans is a considered stand-in, not the brand's actual face. If real font files become available, swap them in directly — the weight-only hierarchy model will transfer without other changes.
- **No real logo or icon set was available.** Generated decks leave a placeholder logo slot; do not invent a Tawuniya mark.
- **Mint and coral have no formal usage precedent beyond the source theme's `accent3`/`accent5`/`accent6` slots** — the "one confidence card" and "alert-only" rules in this doc are this template's own convention, not something confirmed by brand guidelines.
- **No embedded brand photography** was present in the source file (only stock/placeholder imagery) — profile cards and quote-with-photo slides need real images supplied by the user.
