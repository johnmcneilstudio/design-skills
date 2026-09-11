# TriNet — Style Reference
> navy field, orange wing, everything pointing up and to the right

**Theme:** light

TriNet runs on a corporate-editorial logic: white and deep navy grounds, one hot orange that does nearly all of the chromatic work, and a wide secondary palette held in reserve for charts, bands and containers. Display type is Centra No. 2 ExtraBold, all caps, stacked into tight blocks and frequently split across two colors inside a single headline (white line, orange line). The signature device is the wing — the angular mark nested in the final "t" of the wordmark, extracted and scaled up as a graphic motif that always points up and to the right and never rotates, repeats or bleeds. Depth is flat: no gradients, no soft elevation, just hard 16/24/48px zero-blur color offsets and full-bleed color bands. Corners are close to square (0–8px), so the geometry stays crisp against documentary photography that supplies all the warmth.

## Colors

The Figma library publishes these as variables under `brand/primary/*` (orange, navy), `brand/neutral/*` (black, dark-gray, medium-gray) and `neutral/white`; the website exposes the same values as Tailwind tokens (`trinet-orange`, `trinet-navy`, `dark-gray`, `medium-gray`, `light-gray`, `gray-tint`).

### Primary

| Name | Value | Role |
|------|-------|------|
| TriNet Orange | `#FD5000` | The brand's single hot accent — wing motif, headline emphasis lines, CTA fills, logo wing. PMS Orange 021C / C0M74Y100K0 |
| TriNet Navy | `#0B0134` | Default text color, dark section grounds, inverted cards, logo wordmark. PMS 276C / C94M93Y0K79 |
| Web Orange | `#D64100` | The darkened orange the website ships as `trinet-orange` — used wherever orange must carry small text or UI and meet AA contrast |

### Neutral

| Name | Value | Role |
|------|-------|------|
| White | `#FFFFFF` | Page canvas, reversed type, card surfaces |
| Black | `#000000` | Black-only logo output, maximum-contrast type. PMS Process Black |
| Dark Gray | `#54565A` | Secondary body text, meta labels. PMS Cool Gray 11 |
| Medium Gray | `#797D82` | Tertiary text, captions, footer meta. PMS Cool Gray 8 |
| Light Gray | `#DFE1DF` | Hairlines, table borders, quiet panel fills, offset-shadow color. PMS Cool Gray 1 |
| Gray Tint | `#F5F6F5` | Subtle section wash, one step off white |

### Secondary

A shared set of 21 colors in three tonal rows — dark, mid, light. Used for section bands, L-shaped containers, chart series and illustration, never as a replacement for TriNet Orange as the action color.

| Name | Value | Row | Role |
|------|-------|-----|------|
| Dark Orange | `#8F3011` | dark | Deep band grounds, chart series. PMS 174C |
| Gold | `#CB7A00` | dark | Band grounds, chart series. PMS 145C |
| Dark Violet | `#48086F` | dark | Band grounds, event/webinar graphics. PMS 2617C |
| Deep Teal | `#00434A` | dark | Band grounds, report covers. PMS 3165C |
| Dark Magenta | `#6B003D` | dark | Band grounds, campaign graphics. PMS 216C |
| Red | `#C0143C` | dark | Band grounds, chart series. PMS 193C |
| Blue | `#1C02D8` | mid | Saturated fills, chart series. PMS 286C |
| Yellow | `#FFC701` | mid | Highlight numerals, emphasis fills. PMS 116C |
| Violet | `#7F3ED6` | mid | Fills, chart series. PMS 266C |
| Green | `#00B142` | mid | Fills, chart series. PMS 354C |
| Magenta | `#DB0661` | mid | Fills, chart series. PMS 2040C |
| Light Orange | `#FF9E79` | light | Light washes, dark-mode chart tints. PMS 163C |
| Light Blue | `#57CCF6` | light | Light washes, dark-mode chart tints. PMS 305C |
| Light Yellow | `#F9E285` | light | Light washes. PMS 2002C |
| Light Violet | `#B593FF` | light | Light washes. PMS 2645C |
| Turquoise | `#45D8B4` | light | Light washes, success-adjacent graphics. PMS 3385C |
| Pink | `#FF8DCB` | light | Light washes. PMS 2037C |

### Web-only functional colors

Present in the site stylesheet, not in the printed palette.

| Name | Value | Role |
|------|-------|------|
| Note Violet | `#F2ECFB` | Callout/note panel fill, promotional messaging background, offset-shadow color |
| Input Focus | `#0A62E6` | Focus ring on links and form controls |
| Input Error | `#E01021` | Form validation |
| Error Red | `#B91C1C` | Error text |
| Medium Blue | `#0070E0` | Interactive blue in UI chrome |
| Dark Green | `#008531` · `#018130` | Success states; the second value is the AA-compliant variant |
| Disabled Gray | `#3B3B3B` | Disabled controls |
| Checkout Purple | `#661CC8` | Checkout flow accent |
| Checkout tints | `#F3F6FF` · `#F2FBF5` · `#FFF2F2` | Pale info / success / error panel fills |

### Tints

Every primary and secondary color has approved 20 / 40 / 60 / 80 / 100% tints for diagrams, charts and illustrations, in digital and print. Tints are accents only and must never be the predominant color in a piece; text over any tint still has to clear contrast requirements.

## Typography

### Centra No. 2 — the brand typeface
An approachable contemporary geometric sans, close in structure to Futura and Avenir but drawn for screens. Hierarchy is carried by weight, not by width or a second family: **ExtraBold** all caps for display and OOH headlines with tight letterspacing and leading, **Bold** for headlines and subheads, **Medium** for subheads and nav, **Book** for body. The website also ships a Light (300) cut. The distinguishing move is the two-color headline — one clause in white, the next in orange, inside a single tightly leaded all-caps block.
- **Substitute:** web fallback stack is Open Sans then system sans-serif; for geometric fidelity, Poppins, Jost, or Museo Sans
- **Weights:** 300 (web only), 400 Book, 500 Medium, 700 Bold, 800 ExtraBold
- **Sizes:** 12, 14, 16, 18, 24, 36, 40, 48, 56, 64, 72, 80, 100px
- **Line height:** 0.90–1.10 on display, 1.10–1.13 on headings, ~1.44 on body (18/26)
- **Letter spacing:** −0.01em on body, −2px / −3% on large display; OOH headlines set noticeably tighter than default
- **Case:** display and OOH headlines are all caps; headlines, subheads and body are sentence case

### Avenir Next LT Pro — the system typeface
For Microsoft applications (PowerPoint, Word, Outlook), where Centra No. 2 is unavailable. Bold for headline and subhead, Regular for body. Fall back to Arial Regular or Bold only; script, casual and serif faces are excluded.
- **Substitute:** Arial
- **Weights:** Light, Medium (Regular), Bold
- **Deck sizes:** 18pt subhead, 15/18pt body and level-one bullets, 12/15pt levels two and below

### Whitepaper hierarchy — Centra No. 2
A separate, tighter set of published text styles (`Centra No2/Whitepaper/*`) governs long-form documents. It reads quieter than the marketing voice: nothing is set in ExtraBold, headlines are sentence case rather than all caps, and the only all-caps element is an 11px orange kicker. Color carries the hierarchy alongside size — navy for heads, black for the lead paragraph, dark gray for running body, medium gray for captions.

| Style | Family / Weight | Size / Line | Tracking | Case | Color |
|-------|-----------------|-------------|----------|------|-------|
| Kicker / Eyebrow | Bold (700) | 11 / 14 | +1.4px | uppercase | TriNet Orange `#FD5000` |
| H1 — Section head | Bold (700) | 34 / 40 | 0 | sentence | TriNet Navy `#0B0134` |
| H2 — Subsection | Medium (500) | 22 / 28 | 0 | sentence | TriNet Navy `#0B0134` |
| H3 — Minor head | Bold (700) | 16 / 22 | 0 | sentence | Dark Gray `#54565A` |
| Lead paragraph | Book (400) | 17 / 28 | 0 | sentence | Black `#000000` |
| Body | Book (400) | 14 / 23 | 0 | sentence | Dark Gray `#54565A` |
| Caption / Footnote | Medium (500) | 11 / 16 | 0 | sentence | Medium Gray `#797D82` |
| Pull quote | Medium Italic (500) | 20 / 28 | 0 | sentence | TriNet Navy `#0B0134` |

The lead paragraph style is for the opening paragraph only — subsequent paragraphs drop to Body. Note one inconsistency in the source: the H3 row is annotated "Medium" but the published style is Bold; the table above follows the published style.

### Type Scale — Web
From the production website; sizes in px. Marketing pages run considerably larger than the whitepaper hierarchy above — 18px body against 14px, and a hero step that reaches 100px.

| Role | Size | Line Height | Notes |
|------|------|-------------|-------|
| caption | 12 | 18 | |
| body-sm | 14 | 20 | footnotes, meta |
| body-base | 16 | 24 | |
| body | 18 | 26 | site default |
| subheading | 24 | 32 | h5/h6 sit at 24 |
| heading-sm | 36 | 40 | h3 at 36 |
| heading | 40 | 44 | h2 at 40 |
| heading-lg | 48 | 52 | h1 mobile |
| display | 56 | 60 | h1 at ≥768px |
| display-lg | 64 | 68 | h1 at ≥1280px |
| display-xl | 72 | 80 | hero |
| display-2xl | 80 | 88 | hero |
| display-3xl | 100 | 110 | largest web step |

The responsive hero step ramps 36/45 → 48/55 → 60/66 → 72/80 → 80/88 → 100/110 across breakpoints.

## Spacing & Layout

**Base unit:** 4px

**Density:** comfortable

- **Page max-width:** 1280px (container widens to 1536px at the 2xl breakpoint)
- **Gutters:** 16px → 32px (≥640) → 48px (≥768) → 64px (≥1024) → 80px (≥1280) → 96px (≥1536)
- **Nav height:** 116px desktop, 58px mobile; scroll padding accounts for nav + banner + secondary nav
- **Grid:** 12 columns, with 1/2/3/4 and 10-column variants in use
- **Section gap:** not specified in the source material — the stylesheet is utility-driven with no fixed section rhythm
- **Card padding:** not specified in the source material

### Border Radius

The system is effectively square. There is no large-radius card language.

- **default:** 4px
- **sm:** 2px
- **md:** 6px
- **lg:** 8px
- **pill:** 9999px (tags, small controls, avatars)
- **focus ring:** 5px

## Components

### TriNet Wordmark
**Role:** Primary brand signature

Set in all lowercase with the wing mark embedded in the final "t"; the last "t" and the wing together read as a subtle shield. Four approved versions: full-color (navy + orange), reversed-out (white + orange), all white, all black. Minimum height 24px digital / 12pt print. Clear space on all sides is at least one wing-mark width. In running copy the company is written camel case as "TriNet," regardless of the lowercase mark.

### Shield Symbol
**Role:** Shorthand mark for small contexts

The wing joined to the final "t". Reserved for app icons, social avatars and similar constrained spaces — the wordmark is used whenever space permits. Minimum height 20px digital / 8pt print, with one wing-mark of clear space.

### Product Wordmark Lockup
**Role:** Company logo + product name

Available stacked (preferred) and horizontal (when vertical space is tight). Proportions and spacing are fixed and must not be altered or distorted. Clear space is two wing-marks on all sides. Minimum heights: horizontal 25px, stacked 40px.

### Wing Motif
**Role:** The signature graphic device

An enlarged, flat-color wing sized against the height of the format, typically 1/2, 1/3, 1/4, 1/5 or 1/6 of a side; leg thickness commonly 1/3 or 1/6 of the format dimension. Placed toward the right, pointing up and forward, either flush to the edge or inset by a margin equal to the width of its legs. TriNet Orange is the recommended fill.

### Wing-Derived L Container
**Role:** Framing device for messaging and long-form content

The motif adapted into L shapes whose legs may differ in weight and length, used to create square or rectangular containers for copy — including an inverted L that boxes a headline block. Fill with TriNet Navy or a secondary color; TriNet Orange is only permitted when the shape keeps the true wing proportions, though orange may fill the negative space a wing reverses out of.

### Display Headline Block
**Role:** Hero, OOH and campaign headline

Centra No. 2 ExtraBold, all caps, broken across short stacked lines with tight leading and letterspacing. Emphasis is chromatic rather than typographic: the opening clause in white, the payoff clause in TriNet Orange, on a navy ground. Paired with a Bold subhead (for example a three-word service list) and the wordmark-plus-tagline lockup.

### Animated CTA Link
**Role:** Primary inline call to action

Inherits its text color, carries a 1px bottom border, and draws a second underline from 0% to 100% width over 0.3s ease-in-out on hover and focus — 2px standard, 3px in the heavier variant. Variants pin the underline permanently in white or navy. Focus renders a 1px `#0A62E6` ring at 5px radius, offset around the link.

### Headline Highlight Marks
**Role:** Hand-drawn emphasis on a headline span

Two decorations applied to a span inside a headline: a rough brush underline (0.175em tall, clipped to an irregular path) and an enclosing hand-drawn circle (115% wide, 1.35em tall). Both fill with the accent color, animate in over 0.3s after a 0.3s delay, and render statically at full width under `prefers-reduced-motion`.

### Hard Offset Shadow Block
**Role:** Flat depth for cards, images and panels

A zero-blur, zero-spread offset in a solid brand color at 16px, 24px or 48px on both axes, available in any palette color and any opacity step — the system's stand-in for elevation. A 18×16px variant appears at large breakpoints in deep teal and light blue.

### Body Copy Block
**Role:** Long-form text

18/26 Centra No. 2 Book in TriNet Navy. Unordered lists replace bullets with a 0.25em round dot in the current color; ordered lists use generated counters. Bold spans and inline accents pick up an accent color from a theme variable, and links inherit color with the animated underline treatment.

### Pull Quote
**Role:** Emphasis quotation in long-form documents

Centra No. 2 Medium Italic 20/28 in TriNet Navy, preceded by a 3px-wide, 40px-tall TriNet Orange rule with 24px between the rule and the text. No quotation panel, background fill or oversized quote glyph — the orange hairline is the entire device.

### Section Color Band
**Role:** Full-bleed section ground

A flat band in white, Gray Tint, TriNet Navy, TriNet Orange or a secondary color, with type reversed to white or set in navy according to the contrast guidance. Sections are separated by color change rather than by rules or shadows.

### Data Visualization Set
**Role:** Charts in light and dark mode

Multi-color series drawn from the secondary palette, with light-mode combinations checked against light grounds and mid-to-dark hues shifted lighter for dark mode. Tints in 20% steps supply series variation within a single hue.

### Swag Pattern
**Role:** Special-application surface pattern

The wing duplicated on a grid at decreasing scales (1, 0.85, 0.65, 0.5, 0.35) to create upward movement. Spacing between motifs may be opened up to admit copy. Special applications only, and never combined with imagery.

## Do's and Don'ts

### Do
- Set display and OOH headlines in Centra No. 2 ExtraBold, all caps, with tight letterspacing and leading; Bold for subheads, Medium for nav and labels, Book for body.
- Split long headlines across two colors — white for the setup, TriNet Orange for the payoff — inside one tightly leaded block.
- Point the wing motif up and to the right, toward the right side of the layout, at roughly 1/2 to 1/6 of the format's side.
- Fill the wing motif itself with TriNet Orange, and fill derived L-shaped containers with TriNet Navy or a secondary color.
- Keep one wing-mark of clear space around the wordmark and symbol, two around product wordmarks; more is better.
- Use the reversed-out wordmark on navy, the white wordmark on TriNet Orange and on black, and the full-color wordmark on white and on light, high-contrast areas of photography.
- Use `#D64100` in place of `#FD5000` on the web wherever orange carries small text or UI, and check every orange/navy/white pairing against the AA chart.
- Create depth with 16/24/48px zero-blur color offsets and flat color bands.
- Keep radii between 0 and 8px, reserving the pill shape for tags and small controls.
- Write "TriNet" camel case in all copy even though the wordmark is lowercase.

### Don't
- Do not fill a stretched, rotated or otherwise non-wing-proportioned L shape with TriNet Orange — use TriNet Navy or a secondary color.
- Do not point the wing down, rotate it, reverse the layout's orientation, frame content with multiple wings, run it full-bleed, or repeat it as a pattern outside of swag.
- Do not place the wing too low on the page or size it so small that it reads as an icon.
- Do not place the white logo on light secondary colors, or the full-color wordmark on midtone or visually complex photography — use the reversed-out version, or add a subtle dark overlay.
- Do not set the wordmark inside a line of copy as a substitute for the word "TriNet."
- Do not apply transparencies, effects or color overlays to photography, and do not crop so tightly that the real-world context is lost.
- Do not use staged or stock-feeling imagery; docu-style authenticity is the standard.
- Do not let a tint become the predominant color in a piece — tints are accents for diagrams, charts and illustrations.
- Do not carry dark chart colors into light-mode presentations, or mid-to-dark hues into dark mode without shifting them lighter.
- Do not substitute script, casual or serif faces in Office documents — Avenir Next LT Pro, or Arial as the only fallback.
- Do not introduce gradients or soft drop shadows as a depth language.

## Elevation

Effectively flat. Depth comes from the hard offset shadow — a solid brand color at 16px, 24px or 48px on both axes with no blur and no spread — and from color contrast between bands. Soft shadows exist only as minor UI chrome: a 2px/5px 10%-black shade on sticky headers and dropdown edges, and a 2px horizontal 10%-black shade marking the frozen first column of a scrollable table.

## Surfaces

- **Page** (`#FFFFFF`) — default canvas for web and print
- **Gray Tint** (`#F5F6F5`) — quiet section wash, one step off white
- **Light Gray** (`#DFE1DF`) — panels, table fills, hairlines, offset-shadow color
- **Note Violet** (`#F2ECFB`) — callout and promotional-message panels
- **Inverted** (`#0B0134`) — navy sections, ads and covers with reversed-out type
- **Accent Band** (`#FD5000`) — orange full-bleed sections; type on orange is white
- **Secondary Band** (secondary palette) — deep violet, teal, magenta and red grounds for campaign and event graphics

## Imagery

Docu-style photography is the emotional core of the identity: real people in real working contexts, bold color, dramatic light and contrast, and deliberate diversity of race, ethnicity, age and gender. Images run full-bleed or are cropped by wing and L geometry, with the wordmark reversed out in white and the orange wing anchored at the top right. Headline type often overlaps the lower portion of the image. Effects, transparencies and color overlays are prohibited, as are tight crops that strip out context and staged setups that read as stock. Beyond photography, the only graphic vocabulary is the wing motif, its L-shaped derivatives, and occasional loose hand-drawn marks (arrows, sparkles, brush underlines) in orange or white.

## Layout

Full-bleed sections stacked as flat color bands — white, gray tint, navy, orange or a secondary color — with content constrained to a 1280px container on a 12-column grid and gutters that step from 16px to 96px across breakpoints. The navigation bar is a fixed 116px on desktop, 58px on mobile. Compositions are anchored top-left for type and top-right for the wing, which frequently doubles as the structural divider: at a 2:1 aspect it splits the layout into halves, and in square formats it reverses out a container for the headline. Copy blocks are left-aligned and short — headline, two-to-four-word subhead, single CTA. Cards and image blocks sit flat with a hard color offset rather than a shadow. Print and OOH follow the same logic at larger scale: one stacked all-caps headline, one subhead, the wordmark-and-tagline lockup, and the wing in the upper right.

## Similar Brands

Not covered in the source material — the playbook, the Figma working file and the site stylesheet contain no competitive or adjacent-brand references.
