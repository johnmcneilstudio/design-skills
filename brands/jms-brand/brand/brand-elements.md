# JMS Brand Elements

Visual identity system for John McNeil Studio. This is the **current, working system** — it supersedes the 2021 print guidelines (`JMS_BrandGuidelines_v21.pdf`) wherever the two disagree. That PDF is kept only for logo mechanics and brand philosophy, both of which haven't changed; its color palette is legacy and should not be used.

Sources, in order of authority:
1. `johnmcneilstudio.com` (live site — dark, current)
2. `jms-tokens.md` / Figma "JMS Slides Library" (current working token set)
3. `JMS_BrandGuidelines_v21.pdf` (2021 — philosophy, logo, and clearspace only)

---

## 1. Brand truth

**We are a studio.** Not an agency — a maker. [Source: 2021 guidelines, still current voice]

> Our single purpose: making change manifest, with our own hands, in whatever form it takes — bringing it into the world to constantly evolve ourselves, and our client's business.

A catalyst creates a reaction while staying true to itself. JMS creates change through creativity while holding a consistent, recognizable identity. The brand system below is how that consistency gets executed.

**Tone**: declarative, not promotional. Headlines are statements, not pitches — they end in periods, not exclamation points. See `tone-of-voice.md` for the full voice system.

---

## 2. Color

The site and the Slides library now share one dark system. Use these as the primary palette for **all** JMS work — web, decks, social, editorial.

### Core
| Token | Hex | Role |
|---|---|---|
| `--jms-midnight` | `#0B081A` | Default background. The signature deep blue-black — this is the brand's dark mode, not a slide-only choice. |
| `--jms-black` | `#171717` | True black for chrome, contrast wells |
| `--jms-dark-grey` | `#303D52` | Secondary surface / slate |
| `--jms-medium-grey` | `#97ADC5` | Body text on dark, dividers, photo overlays |
| `--jms-light-grey` | `#DBE3E5` | Soft light surface (rare — light sections only) |
| `--jms-off-white` | `#F2F2ED` | Warm off-white, used over photography |
| `--jms-true-white` | `#FFFFFF` | Default text color on midnight |
| `--jms-magenta` | `#FF00FF` | Brand accent — use sparingly, never as a dominant field |

### Accent / chart palette
| Token | Hex |
|---|---|
| `--jms-purple` | `#864DFF` |
| `--jms-blue` | `#33A6E3` |
| `--jms-green` | `#1DC356` |
| `--jms-yellow` | `#E8D11F` |
| `--jms-pink` | `#EA12C0` |
| `--jms-neutral-grey` | `#707070` |

**Rule**: don't run more than 3 colors in one layout, magenta included. Slate/midnight anchors; color pops.

### Gradients — the brand "moment"
```css
--jms-grad-magenta-purple: linear-gradient(90deg, #FF00FF 0%, #864DFF 100%);
--jms-grad-blue-green:     linear-gradient(90deg, #1DC356 0%, #33A6E3 100%);
--jms-grad-yellow-pink:    linear-gradient(90deg, #E8D11F 0%, #EA12C0 100%);
--jms-grad-multi:          linear-gradient(90deg, #EA12C0 0%, #864DFF 35%, #33A6E3 70%, #1DC356 100%);
```
Content-specific pairs (used to color-code workstreams):
```css
--jms-grad-strategy:   linear-gradient(90deg, #E8D11F 0%, #EA12C0 100%);  /* yellow → pink */
--jms-grad-creative:   linear-gradient(90deg, #EA12C0 0%, #864DFF 100%);  /* pink → purple */
--jms-grad-production: linear-gradient(90deg, #33A6E3 0%, #1DC356 100%);  /* blue → green */
```

**Usage rules**
- `--jms-grad-multi` is reserved for one moment per piece — a closing line, a manifesto payoff, a divider rule. Overuse kills the effect.
- Apply gradient to a few words max via `background-clip: text`. Never gradient body copy or long passages.
- Angle at 45° for a more dynamic feel where the layout allows it; 90° (left-right) is the safe default for text and hairlines.
- Hairline dividers (1px, `--jms-grad-multi`) frame manifesto/pull-quote blocks, above and below.

---

## 3. Typography

Typeface: **Poppins**, throughout, all channels. Weights: ExtraLight (200), Light (300), Regular (400), SemiBold (600).

| Token | Use | Weight | Size | Line-height | Tracking |
|---|---|---|---|---|---|
| `--jms-type-title` | Cover / hero | ExtraLight | 140px | 105% | -3% |
| `--jms-type-h1` | Section opener | ExtraLight | 86px | 115% | -2% |
| `--jms-type-h2` | Section heading | ExtraLight | 64px | 115% | -2% |
| `--jms-type-subhead` | Lead paragraph | ExtraLight | 48px | 120% | 0% |
| `--jms-type-subhead-sm` | Minor heading | Light | 36px | 135% | +2% |
| `--jms-type-body-lg` | List / bullet items | Light | 32px | 48px | 0% |
| `--jms-type-body-md` | Default supporting copy | Regular | 22px | 33px | +1.5% |
| `--jms-type-body-sm` | Dense copy, footnotes | Regular | 18px | 27px | +3% |
| `--jms-type-eyebrow` | UPPERCASE labels | SemiBold | 14px | 21px | +6% |
| `--jms-type-caption` | Captions, fine print | Regular | 16px | 24px | +3% |

**Rules**
- ExtraLight is the brand voice at 36px and up. Thinness is the look — never bold a headline.
- Emphasis comes from gradient or color, never from weight.
- Headline sentences end with a period — declarative, not promotional.
- Eyebrows are always uppercase, SemiBold, +6% tracking.

### 3.1 Web typography — translating the deck tokens

The table above is deck-native (fixed px on a 1920px slide canvas) and doesn't carry over to web as-is. Three things need to change before these become real CSS tokens:

**Tracking must be in `em`/`px`, not `%`.** `letter-spacing` isn't a valid CSS property in percent. Converted (approximate, relative to each token's own font-size):

| Token | Tracking (deck) | Tracking (web, em) |
|---|---|---|
| `--jms-type-title` | -3% | `-0.03em` |
| `--jms-type-h1` | -2% | `-0.02em` |
| `--jms-type-h2` | -2% | `-0.02em` |
| `--jms-type-subhead` | 0% | `0em` |
| `--jms-type-subhead-sm` | +2% | `0.02em` |
| `--jms-type-body-md` | +1.5% | `0.015em` |
| `--jms-type-body-sm` | +3% | `0.03em` |
| `--jms-type-eyebrow` | +6% | `0.06em` |
| `--jms-type-caption` | +3% | `0.03em` |

**No responsive scale is defined — decks don't need one, web does.** The two largest tokens (`title` 140px, `h1` 86px) will overflow small viewports with no fallback. Recommended `clamp()` ranges (min = ~mobile, max = current deck value), pending a real audit against the live site:

```css
--jms-type-title: clamp(2.75rem, 6vw + 1rem, 8.75rem);   /* 44px → 140px */
--jms-type-h1:    clamp(2.25rem, 4vw + 1rem, 5.375rem);  /* 36px → 86px */
--jms-type-h2:    clamp(2rem, 3vw + 1rem, 4rem);          /* 32px → 64px */
```
Everything `subhead` and below is close enough to body-text scale that it can stay fixed-`rem` without a fluid clamp.

**No UI/component type roles exist yet.** Decks have no buttons, nav, tags, or form fields, so the token table is silent on them. Until a real component audit happens: use `--jms-type-body-sm` (18px/Regular) as the default for nav links and body-adjacent UI text, `--jms-type-eyebrow` for buttons and tags (matches its existing "UPPERCASE label" role), and treat **Poppins Regular** as the de facto default UI face — it isn't currently named as one anywhere in the brand system, which is a gap worth closing explicitly rather than leaving implicit.

```css
:root {
  --jms-font-family: 'Poppins', sans-serif;
  --jms-type-title: clamp(2.75rem, 6vw + 1rem, 8.75rem);
  --jms-type-h1: clamp(2.25rem, 4vw + 1rem, 5.375rem);
  --jms-type-h2: clamp(2rem, 3vw + 1rem, 4rem);
  --jms-type-subhead: 3rem;
  --jms-type-subhead-sm: 2.25rem;
  --jms-type-body-lg: 2rem;
  --jms-type-body-md: 1.375rem;
  --jms-type-body-sm: 1.125rem;
  --jms-type-eyebrow: 0.875rem;
  --jms-type-caption: 1rem;
}
```

[Guessing] These clamp ranges are derived from the existing deck px values, not measured against the live site's actual rendered CSS — confirm against DevTools before shipping.

---

## 4. Layout

- Canvas: 16:9 as the deck/video reference (1920×1080); web scales fluidly from the same type/spacing ratios.
- Default background `--jms-midnight`, default text `--jms-true-white`.
- Outer padding ~4.2% of frame width (80px @ 1920).
- Left-aligned system throughout — headline left edge sets the margin for everything below it. Right side is left open for imagery or breathing room, not filled defensively.
- Three-column info blocks: even columns, generous gutters, no visible rules. Each column opens with an em-dash (—) on its own line.
- No drop shadows, no glows, no rounded card containers. Flat, typographic, confident — this applies everywhere, not just slides.

---

## 5. Logo

Files live in `assets/logo/` at repo root (mark, wordmark, and lockup, in white/black/full-color variants — see that folder's README for the full list). This section is the usage spec; that folder is just the file location.

*(Mechanics below are unchanged from the 2021 guidelines — still current.)*

- The mark centers on the **"S" in Studio** — splashes emerge from the S, standing for the many makers and skills inside JMS. Animated versions exist for film/TV; static versions for print/web.
- A separate wordmark ("John McNeil Studio") exists for use on web, optionally paired with the mark.
- **Clear space**: minimum clear space = the x-height of the logo (height of the "J"). On web/app where space is tight, top/bottom clear space can shrink to half the x-height — never less.
- **Minimum size**: 0.75in / 19mm in print, 75px wide on web/video. Never smaller.
- Treat the mark as a locked asset — don't recreate or reinterpret it per-piece.

---

## 6. Graphic elements

- **The Splash**: a multicolor burst symbolizing creative/catalytic energy and range across capabilities. Photographic, not illustrated. Appears at high-impact moments only — covers, closers, hero sections — never as filler decoration.
- **The gradient**: the restrained, contained cousin of the splash — hairline dividers and single-line text treatments (see §2).
- Don't combine splash + full gradient treatment in the same moment; pick one per key beat.

---

## 7. Photography

**Black and white is the current standard** — this supersedes the 2021 guideline's colored-gel headshot treatment, which is no longer in use on the live site.

- All documentary/editorial photography — studio candids, team-at-work shots, gallery/event imagery — runs in black and white. This includes team headshots, shot on a light/off-white card background, not colored gels.
- Color is not spread across photography at all. It's isolated entirely to the splash/powder-explosion imagery (see §6) and the gradient system (see §2) — both of which are graphic elements, not photographic treatments of people or space.
- This creates a clean split: **black and white = real, documentary, human**; **color = graphic, decorative, brand-voice moments**. Don't blend the two — a colorized documentary photo or a black-and-white splash both break the system.
- JMS's people-facing photography represents a diverse range of makers — the "who" of the studio — shot candidly, not posed stock-generic.

---

## 8. What NOT to do

- Don't use the 2021 guideline's light palette (Sand/Navy/Slate/`#EC008B` magenta) — legacy, superseded by §2.
- Don't bold headline type for emphasis — use gradient or accent color instead.
- Don't gradient more than one text moment per piece.
- Don't add shadows, glows, or rounded containers.
- Don't run more than 3 brand colors in a single layout.
- Don't recreate the logo/mark from scratch — use the locked asset.
- Don't colorize documentary/team photography — black and white only; color lives in the splash and gradients, not in photos of people or space.
