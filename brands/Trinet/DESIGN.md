# TriNet — Design Reference

> Clear, human and restrained. Typography establishes hierarchy; photography supplies warmth; orange provides emphasis.

**Status:** Current JMS working direction  
**Last reviewed:** September 14, 2026  
**Default theme:** Light

This reference defines the current design direction for TriNet campaign pages, landing pages, presentations and editorial materials developed with JMS.

It builds on the established TriNet identity while simplifying its expression. Layouts should feel light, direct and editorial rather than heavily branded or decorated. Use strong typography, generous whitespace, candid photography and restrained color.

Where this reference differs from older TriNet materials, follow this document for new JMS work. Existing corporate templates and production pages may continue to use legacy treatments when consistency with those materials is required.

---

## Principles

### Clear before clever

The communication should be understandable before the design calls attention to itself. Each section should communicate one primary idea.

### Human and precise

Lead with language people recognize. Follow it with concise supporting copy that clearly explains the business value.

### Restraint creates emphasis

Not every element needs a color, icon, card or graphic device. Typography, spacing and photography should do most of the work.

### Editorial, not templated

Layouts should feel intentionally composed rather than assembled from repeated marketing modules.

### Real people, real situations

Photography should show believable people in genuine working environments. Avoid generic corporate stock conventions.

---

## Colors

The core TriNet palette remains intact, but its use is more restrained than in older brand materials.

### Primary

| Name | Value | Role |
|---|---|---|
| TriNet Orange | `#FD5000` | Primary brand accent, CTA fills, campaign emphasis and logo wing |
| TriNet Navy | `#0B0134` | Primary text, dark surfaces and reversed sections |
| Web Orange | `#D64100` | Accessible orange for small text and interactive UI |
| White | `#FFFFFF` | Primary page canvas and reversed text |

Orange should provide emphasis, not dominate every composition. Large orange fields should be used intentionally rather than as a default section treatment.

### Neutral

| Name | Value | Role |
|---|---|---|
| Black | `#000000` | Maximum-contrast text and black-only output |
| Dark Gray | `#54565A` | Secondary body copy and metadata |
| Medium Gray | `#797D82` | Captions and tertiary information |
| Light Gray | `#DFE1DF` | Borders, separators and quiet panels |
| Gray Tint | `#F5F6F5` | Light section background |
| White | `#FFFFFF` | Default canvas and card surface |

Light neutral backgrounds should carry most pages. Alternate between white and subtle gray only when a section change needs clarification.

### Secondary

The broader TriNet palette remains available for:

- Data visualization
- Approved campaign systems
- Social content
- Event materials
- Functional categorization

It should not become the default landing-page palette.

| Name | Value |
|---|---|
| Dark Orange | `#8F3011` |
| Gold | `#CB7A00` |
| Dark Violet | `#48086F` |
| Deep Teal | `#00434A` |
| Dark Magenta | `#6B003D` |
| Red | `#C0143C` |
| Blue | `#1C02D8` |
| Yellow | `#FFC701` |
| Violet | `#7F3ED6` |
| Green | `#00B142` |
| Magenta | `#DB0661` |
| Light Orange | `#FF9E79` |
| Light Blue | `#57CCF6` |
| Light Yellow | `#F9E285` |
| Light Violet | `#B593FF` |
| Turquoise | `#45D8B4` |
| Pink | `#FF8DCB` |

When multiple secondary colors are used, establish a clear reason for the color system. Do not apply colors simply to create visual variety.

### Functional colors

| Name | Value | Role |
|---|---|---|
| Input Focus | `#0A62E6` | Focus rings and selected controls |
| Input Error | `#E01021` | Form validation |
| Error Red | `#B91C1C` | Error text |
| Medium Blue | `#0070E0` | Interactive UI |
| Dark Green | `#008531` | Success states |
| Disabled Gray | `#3B3B3B` | Disabled controls |

### Tints

Approved tints may be used for charts, diagrams and subtle information panels. A tint should not become the predominant color of a page unless the specific campaign system calls for it.

Text placed over any tint must meet accessibility contrast requirements.

---

## Typography

## Avenir Next LT Pro — Current working typeface

Avenir Next LT Pro is the primary typeface for current JMS campaign, landing-page, presentation and editorial work.

Hierarchy should come from scale, weight, spacing and composition. Avoid creating a separate style for every semantic heading level.

### Weights

- Regular for body copy
- Medium for labels and supporting headings
- Demi or Bold for headings and calls to action
- Italic for selective editorial emphasis
- Heavy weights should be used sparingly

### Case

- Display headlines: sentence case
- Section headings: sentence case
- Card headings: sentence case
- Body copy: sentence case
- Buttons: sentence case
- Metadata and functional labels: sentence case by default

All-caps headlines belong to older TriNet expression and should not be introduced into new JMS layouts unless explicitly requested.

### Web type scale

| Style | Size / Line | Primary use |
|---|---:|---|
| `TriNet/Display — Large` | 64 / 68 | Large landing-page hero |
| `TriNet/Display` | 48 / 52 | Standard hero and editorial title |
| `TriNet/Heading — Large` | 40 / 44 | Major section heading |
| `TriNet/Heading` | 24 / 32 | Card and subsection heading |
| `TriNet/Body — Large` | 18 / 26 | Lead and prominent supporting copy |
| `TriNet/Body` | 16 / 24 | Standard body copy |
| `TriNet/Label` | 16 / 24 | Small headings and utility labels |
| `TriNet/Button` | 18 / 26 | Primary and secondary actions |
| `TriNet/Meta` | 14 / 20 | Captions, metadata and supporting links |

The core hierarchy is:

**64 → 48 → 40 → 24 → 18 → 16 → 14**

Do not reintroduce separate 32px H2, 18px H3, 16px small H3 or multiple 14px H4 styles. HTML semantics and visual styles do not need a one-to-one relationship.

### Responsive display scale

Display type should reduce intentionally rather than through arbitrary intermediate sizes.

Recommended behavior:

- Large desktop: 64 / 68
- Desktop and tablet: 48 / 52
- Small tablet and mobile: approximately 40 / 44 or 36 / 40
- Long mobile headlines may reduce further when necessary

Headlines may break across two or three lines. Do not force a one-line headline at the expense of legibility or composition.

### Campaign emphasis

The italicized and straight-underlined word **really** is a campaign-specific treatment for:

**What do you _really_ need from HR?**

Rules:

- Use sentence case.
- Capitalize “What.”
- Italicize only the intended emphasis word.
- Use a clean, straight underline.
- Keep the underline visually controlled.
- Do not add arrows, sparkles or additional emphasis marks.

Do not turn this treatment into a universal TriNet headline style.

## Centra No. 2 — Existing corporate materials

Centra No. 2 appears throughout existing TriNet web and brand materials. Retain it when matching an established production page, template or corporate asset that already uses it.

Do not mix Centra No. 2 and Avenir Next casually within a single experience.

Legacy treatments associated with Centra include:

- ExtraBold all-caps display type
- Tight stacked headline blocks
- Two-color orange and white headlines
- Large corporate campaign typography

These treatments should not automatically carry into new JMS work.

## Microsoft Office

Use Avenir Next LT Pro when it is installed on the recipient’s system.

Fallback:

1. Avenir Next LT Pro
2. Arial

Do not use script, casual or serif substitutions.

For editable PowerPoint files:

- Turn off font embedding.
- Allow the file to use the locally installed Avenir Next LT Pro family.
- Confirm the recipient has the required fonts.
- Use solid backgrounds.
- Avoid unnecessary diagonal patterns, orange rules and decorative flourishes.

## Whitepapers and datasheets

Long-form materials should be quieter than campaign pages.

| Style | Weight | Suggested size / line | Color |
|---|---|---:|---|
| Document title | Bold | 30–34 / 36–40 pt | TriNet Navy |
| Section heading | Bold | 20–22 / 26–28 pt | TriNet Navy |
| Subsection heading | Demi/Bold | 14–16 / 19–22 pt | Dark Gray |
| Lead paragraph | Regular | 12–13 / 18–20 pt | Black |
| Body | Regular | 10.5–11 / 15–17 pt | Dark Gray |
| Caption | Regular/Medium | 9–10 / 13–15 pt | Medium Gray |
| Pull quote | Medium Italic | 16–20 / 22–28 pt | TriNet Navy |

Primary printed body copy should generally not fall below 9.5pt. Always print a physical proof before approving a long-form document.

---

## Spacing and layout

**Base unit:** 4px  
**Density:** Comfortable  
**Default alignment:** Left  
**Grid:** 12 columns

### Page width

- Standard content container: approximately 1280px
- Wide layouts may extend to approximately 1536px
- Reading-width copy should remain substantially narrower

### Gutters

Recommended responsive progression:

- Mobile: 16–24px
- Small tablet: 32px
- Tablet: 40–48px
- Desktop: 64–80px
- Large desktop: up to 96px

### Section rhythm

Use generous spacing to distinguish blades before adding borders, color blocks or graphics.

Typical section spacing:

- Mobile: 64–80px
- Tablet: 80–112px
- Desktop: 112–160px

These values are guidelines rather than mandatory component dimensions.

### Cards

Cards should only be introduced when they clarify grouping, comparison or interaction.

Recommended card behavior:

- Light or white surface
- 24–40px internal padding
- Minimal border or no border
- Little or no shadow
- Clear typographic hierarchy
- Consistent content alignment

Do not place every paragraph inside a card.

---

## Border radius

Geometry should remain crisp and controlled.

- Default: 4px
- Small: 2px
- Medium: 6px
- Large: 8px
- Pill: reserved for tags, chips and compact controls
- Focus ring: 5px when required by the component

Avoid large-radius consumer-app cards unless a product requirement establishes that pattern.

---

## Components

## TriNet wordmark

Use the approved TriNet wordmark artwork.

Approved versions:

- Full color
- Reversed white and orange
- All white
- All black

In running copy, write the company name as **TriNet**.

Do not redraw, approximate or rebuild the logo.

## Hero

A hero should communicate the page’s primary idea quickly.

Typical structure:

1. Headline
2. Concise supporting line
3. Primary action, form or required next step
4. One intentional image when photography adds meaning

For campaign pages, the hero may be only an image, headline and subhead.

Avoid:

- Multiple competing CTAs
- Decorative eyebrow labels
- Icon clusters
- Floating graphic ornaments
- Long introductory paragraphs
- Several messages competing above the fold

## Human headline and precise support

The headline should express the human idea. The supporting line should explain it clearly and concretely.

Do not make both lines equally emotional or equally technical.

Example:

**What do you really need from HR?**

Every business is different. So is what it needs from HR.

## Recognition prompts

Questions such as:

- I’m hiring and growing fast.
- My HR is taking too much of my time.
- I’m worried about what I don’t know.
- I need better benefits to compete.
- My business has gotten too complex to handle HR myself.

are recognition prompts, not navigation elements.

Their job is to help visitors recognize their situation before moving into the form. They should not appear to branch into different pages or product categories unless the experience genuinely supports that behavior.

## Content cards

Use cards for:

- Distinct business situations
- Comparisons
- Short expert perspectives
- Related resources
- Clearly grouped capabilities

A card should contain one primary idea. Do not decorate cards with icons merely to differentiate them.

## Form and conversion panel

The form is the destination of the page, not an administrative afterthought.

Keep the surrounding design quiet:

- Clear form title
- Short explanation
- Visible labels
- Accessible focus and error states
- Minimal adjacent messaging
- No unnecessary illustrations

## Proof and statistics

Use large, factual proof points with concise labels.

Recommended heading:

**TriNet at a glance**

Avoid inventing an additional campaign-style headline when the section’s function is factual proof.

## Awards and recognition

Use actual approved award artwork supplied or published by TriNet. Do not approximate award logos.

Keep award strips compact and separate from company statistics when possible.

## Calls to action

Primary CTA:

- Orange fill
- Clear sentence-case label
- Strong contrast
- No decorative arrow unless the component system requires one

Secondary CTA:

- Text link or restrained outline
- Clear hover and focus state

## Icons

Use icons only when they perform a functional or informational role.

Approved uses include:

- Product UI
- Functional controls
- Established diagrams
- Checklists
- Existing TriNet icon-library applications

For simplified editorial materials, existing icons may be converted to one color to better integrate with the restrained system.

Do not introduce icons simply because a section has three or four columns.

## Check marks

Check marks are appropriate for concise benefits, requirements and included features. Keep them small, consistent and subordinate to the typography.

---

## Do’s and don’ts

### Do

- Use Avenir Next LT Pro for current JMS work.
- Set headlines in sentence case.
- Establish clear jumps in the simplified type hierarchy.
- Use white and light neutral backgrounds as the default.
- Use orange as an intentional accent.
- Let typography and spacing carry the design.
- Use candid, context-rich photography.
- Show real-feeling owners, employees and teams.
- Allow images to become large when they provide the emotional center.
- Use a 12-column grid.
- Keep components crisp and restrained.
- Use existing TriNet icons when they add information.
- Keep proof sections direct and factual.
- Test body copy at actual printed size.
- Check color contrast and keyboard focus states.

### Don’t

- Do not default to all-caps display headlines.
- Do not use large extracted wing graphics as a routine layout device.
- Do not build layouts from repeated L-shaped containers.
- Do not add orange dashes, arrows, sparkles or decorative marks.
- Do not add icons to every card.
- Do not turn every section into a large color field.
- Do not use hard offset shadows as the default depth language.
- Do not rely on decorative gradients.
- Do not introduce large rounded cards without a functional reason.
- Do not use generic stock-feeling business imagery.
- Do not crop away all evidence of the working environment.
- Do not create award-logo approximations.
- Do not treat recognition questions as navigation when they lead only to a form.
- Do not make print body copy too small to read comfortably.
- Do not embed Avenir Next in PowerPoint when editability is required.

---

## Elevation

The current system is predominantly flat.

Use separation in this order:

1. Whitespace
2. Background change
3. Fine border
4. Very subtle shadow, only when necessary

Avoid large, colored, zero-blur offset shadows in current JMS work. Those belong to the earlier expression and may be retained only when matching an established legacy asset.

---

## Surfaces

### Page

`#FFFFFF`

The standard canvas for campaign pages, landing pages and editorial materials.

### Quiet section

`#F5F6F5`

Used to distinguish a section without creating a strong visual interruption.

### Panel

White or a restrained light gray with an optional fine border.

### Inverted

`#0B0134`

Use selectively for a meaningful pause, proof section or final CTA. Avoid alternating every section between light and dark.

### Orange

`#FD5000`

Use for focused campaign moments and calls to action. It should feel intentional when it occupies a large area.

### Secondary color

Reserved for approved campaign systems, social executions, charts and event applications.

---

## Imagery

Photography is the emotional counterweight to the restrained design system.

### Direction

Use:

- Candid, real-feeling moments
- Small-business owners and teams
- Genuine working environments
- Natural or direct high-flash lighting
- Strong contrast and believable color
- People engaged with one another or their work
- Deliberate representation across race, age, gender and profession
- Horizontal images that support responsive web crops
- Portraits that retain environmental context

Not every person needs to be using a computer. Look for conversations, gestures, movement, preparation and the ordinary details of running a business.

### Avoid

- Generic corporate stock photography
- Staged handshakes
- Forced group poses
- Artificially perfect offices
- People staring at laptops without a meaningful story
- Excessive retouching
- Heavy color overlays
- Tight crops that remove the business context
- Distorted or stretched source images

### Composition

Photography may:

- Run full width
- Occupy one side of a split layout
- Interrupt a structured page as an editorial seam
- Replace one card in an otherwise typographic grid
- Appear as a large portrait beside proof or supporting content

Photography should not be added merely to fill an empty module.

### Asset provenance

Record whether each image is:

- Supplied by TriNet
- Licensed stock
- Commissioned
- AI-generated
- Edited from a supplied source

Do not describe an AI-generated asset as stock photography. Retain the original source and approval history for client-delivered assets.

### Web image preparation

Keep the original PNG or highest-quality source file as the master.

For implementation:

- Export WebP and, where supported, AVIF derivatives.
- Generate multiple responsive sizes.
- Avoid repeatedly recompressing already compressed files.
- Preserve a high-quality master outside the web build.

Recommended master dimensions:

| Use | Suggested master width |
|---|---:|
| Full-width hero | 2000–2400px |
| Split hero or editorial feature | 1600–2000px |
| Large card | 1200–1600px |
| Standard card or thumbnail | 800–1200px |

Dimensions are only one measure of quality. Inspect sharpness, focus, compression artifacts and the effective crop at the intended display size.

---

## Layout

Layouts should feel composed, editorial and easy to scan.

### Default behavior

- Light page canvas
- Twelve-column structure
- Strong left alignment
- Generous margins
- Large typographic moments
- One primary idea per blade
- Photography used as an intentional interruption
- Restrained transitions between sections

### Landing pages

A typical landing page may contain:

1. Simple hero
2. Supporting context or campaign introduction
3. Recognition prompts or primary value proposition
4. Form or conversion point
5. Supporting capabilities
6. Proof
7. Awards or reassurance
8. Final CTA

This is not a required template. Remove any section that does not contribute to understanding or conversion.

### Long-form and gated resources

Keep gated-resource pages especially simple:

1. Resource title
2. Concise value proposition
3. Image of the document or one relevant photograph
4. Form
5. One compact proof or supporting-content section

Do not rebuild a full corporate website beneath every gated form.

### Cards and grids

Introduce a grid only when the content contains comparable items. Varying the width or placement of one image can prevent a page from feeling mechanically modular.

### Decorative graphics

No graphic flourish should be added solely because a layout feels empty. First reconsider:

- Scale
- Alignment
- Whitespace
- Image choice
- Copy length
- Section rhythm

---

## Legacy and approved exceptions

The following remain part of historic or broader TriNet expression but are not defaults for current JMS work:

- Centra No. 2 ExtraBold display typography
- All-caps stacked headlines
- White-and-orange split headlines
- Oversized extracted wing motifs
- Wing-derived L containers
- Hard colored offset shadows
- Large secondary-color section bands
- Repeated wing patterns
- Loose arrows, sparkles and brush decorations

Use these only when:

- Matching an existing campaign
- Extending an established production experience
- Required by a TriNet-owned template
- Specifically requested and approved

The official logo and its embedded wing remain core brand assets.

---

## Similar design references

The current direction is closer to restrained editorial and modern professional-services design than to highly decorated corporate campaign systems.

Useful qualities to reference:

- Strong editorial typography
- Clean gated-resource pages
- Generous white space
- Bold, candid photography
- Clear conversion paths
- Minimal functional iconography
- Simple factual proof sections

References should inform composition and restraint, not introduce another brand’s visual devices.

---

## Final review checklist

Before delivery, confirm:

- Avenir Next LT Pro is used consistently.
- Headlines are sentence case.
- The simplified type scale is followed.
- Orange is restrained and purposeful.
- Decorative arrows, dashes and flourishes have been removed.
- Icons serve a clear function.
- Photography feels candid and context-rich.
- Image provenance is documented.
- Web images have responsive WebP or AVIF versions.
- Print body copy has been physically proofed.
- Forms meet accessibility requirements.
- Award marks are official assets.
- Recognition prompts do not imply false navigation.
- PowerPoint fonts remain editable for the recipient.
- The page communicates its central idea within a few seconds.