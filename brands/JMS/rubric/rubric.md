# JMS Design Rubric — Version 1.0
### The framework for judging whether work is ordinary, good, or exceptional.

This is not a brand guide or a design system. It contains no tokens, no components, no color hex codes. It is the reasoning process a Design Director uses to evaluate work, and the reasoning process a designer (human or AI) should run *before* work is shown. Apply it to any medium: websites, decks, social assets, motion, product UI, print, campaigns.

Every section follows the same structure: Why it matters → Principles → Best practices → Common mistakes → Anti-patterns → Observable signals → Reviewer questions → 1–10 scoring rubric → Revision heuristics.

**How to use the scores:** 1–3 = fails craft standard, not shippable. 4–5 = functional but forgettable, needs a full pass. 6–7 = solid, ships with minor fixes. 8–9 = exceptional, teach from it. 10 = reserved for work that redefines the brief.

---

## 1. Typography

### Why it matters
Typography is the primary carrier of voice before a single word is read. In work with no photography, no color, no motion — type alone must produce hierarchy, tone, and pace. It is also the fastest way to tell whether a designer has training or is guessing.

### Principles
- Type is a system of contrast (size, weight, spacing) — not a font choice.
- A typeface's thinness, weight, or personality *is* the message; never fight it with competing emphasis devices.
- Every typographic decision should be justifiable by a reading order, not by taste.
- Fewer weights, used more deliberately, always outperform more weights used loosely.

### Best practices
- Establish no more than 4–6 type "levels" (title, heading, subhead, body, caption, label) per artifact and use them with total consistency.
- Let line-length govern size: body copy target 45–75 characters per line regardless of viewport.
- Track large light-weight display type slightly negative; track small caps/labels slightly positive. Optical correction over mathematically "clean" numbers.
- Baseline-align mixed type sizes sharing a row; never eyeball it.
- Punctuate headlines with intent — a period changes a headline from a promise to a statement.

### Common mistakes
- Bolding a headline to make it "pop" instead of increasing size, isolating it, or using color/contrast.
- More than 3 typefaces (or type styles pretending to be families) in one artifact.
- Centered body copy longer than one line.
- Letting software defaults (auto line-height, auto tracking) ship unreviewed.

### Anti-patterns
- Emphasis by underline, all-caps, AND bold simultaneously on the same phrase ("shouting three times").
- Justified body text without proper hyphenation control (rivers of white space).
- Using a display face at body-copy sizes because "it's the brand font."

### Observable signals of quality
- A viewer can name what's most important on the page within 2 seconds without reading a single word.
- Removing all color, the hierarchy still reads correctly in grayscale.
- Every type size on the page can be explained by its role, not by "it looked right."

### Reviewer questions
- If I squint until the words blur, what shape draws my eye first — is that the intended message?
- Could this same hierarchy be achieved with one fewer weight or size?
- Does the headline read like it was written to be said aloud, or written to fill a box?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Default software styles; no evident hierarchy logic; multiple competing emphases. |
| 4–5 | Hierarchy exists but is inconsistent across the piece; sizes not systematized. |
| 6–7 | Clear, consistent type system; minor optical spacing issues. |
| 8–9 | Hierarchy is instant and effortless; type carries tone without other devices. |
| 10 | Type alone could sell the idea with every other element removed. |

### Revision heuristics
- If hierarchy is unclear: cut levels, don't add them. Merge similar-weight elements into one level.
- If a headline feels flat: change size or isolation before reaching for bold or color.
- If body copy feels heavy: increase line-height before decreasing size.

---

## 2. Hierarchy

### Why it matters
Hierarchy is the sequencing of attention. Without it, every element competes for the same first glance and the viewer must do the designer's job of deciding what matters.

### Principles
- There is exactly one first read per screen or spread. Two "most important" things means neither is.
- Hierarchy is built from contrast — of size, weight, color, position, isolation, or motion — not from decoration.
- Hierarchy should match the business/communication priority, not the order content was handed over in.

### Best practices
- Design the "2-second version" first: what should survive if everything else is removed?
- Use a single dominant contrast lever per screen (usually size) and let secondary levers (color, weight) support it.
- Group related items so the eye treats them as one hierarchy unit, not several.

### Common mistakes
- Treating every piece of client-supplied content as equally important ("everything is a headline").
- Hierarchy that follows a template's slots rather than the actual message priority.
- Adding visual weight to fix a hierarchy problem instead of removing content.

### Anti-patterns
- Three or more elements at identical visual weight fighting for first read.
- Hierarchy that changes rules screen-to-screen with no logic (headline is biggest here, smallest there).

### Observable signals of quality
- A first-time viewer, asked "what is this about," gives the same answer as the strategy brief.
- Squint test: the blurred composition still shows one clear focal point.
- Removing the second-most-important element doesn't change what the piece is "about."

### Reviewer questions
- What is the one thing this piece must communicate in 2 seconds — is that visually first?
- Is there a competing focal point robbing attention from the intended one?
- Would a stranger read this in the order I intended, unprompted?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | No discernible order; everything is loud or everything is quiet. |
| 4–5 | An order exists but requires effort to find. |
| 6–7 | Clear primary/secondary/tertiary read, minor competition. |
| 8–9 | Instant, unambiguous sequence; every element earns its position. |
| 10 | The hierarchy itself tells the story, independent of the words used. |

### Revision heuristics
- If two elements compete: demote one — in size, in color intensity, or in position — rather than promoting the other further.
- If nothing stands out: don't add more emphasis everywhere; remove emphasis from everything but one thing.

---

## 3. Layout & Composition

### Why it matters
Layout is the architecture that holds every other decision. Good composition makes complex information feel inevitable; bad composition makes simple information feel cluttered.

### Principles
- Every element's position should be justifiable relative to the others — nothing floats by accident.
- Asymmetry, used deliberately, creates more energy and sophistication than centered symmetry.
- Negative space is a designed element, not the absence of one.
- Alignment is the cheapest, highest-leverage tool for perceived quality.

### Best practices
- Establish a small number of alignment lines (a "spine") and tie every element to one.
- Use consistent margins that scale predictably across breakpoints/formats — not ad hoc per screen.
- Let large images or explosive visual moments bleed off the edge rather than float in a box; let quiet content sit inside generous margins.
- Compose in thirds or with an intentional off-center anchor rather than defaulting to centered.

### Common mistakes
- Centering everything by default because it's "safe."
- Inconsistent margins between otherwise-similar screens/slides.
- Elements that are almost aligned (off by a few pixels) — worse than obviously unaligned.
- Filling space because it's empty, not because content needs it.

### Anti-patterns
- Symmetrical, centered layouts on every single screen of a multi-screen piece (monotonous, amateur "PowerPoint" tell).
- Decorative shapes added purely to fill a quadrant that feels sparse.
- Content boxed into cards with shadows/borders when a grid alone would organize it.

### Observable signals of quality
- Drawing alignment guides over the piece reveals a small number of straight lines nearly everything touches.
- The composition still feels balanced with all text replaced by gray boxes (weight/structure test).
- Removing any one element leaves a visible, intentional gap — nothing is filler.

### Reviewer questions
- Can I draw fewer than 5 lines that most elements align to?
- Is every empty area doing a job (separation, breathing room, pacing) or is it just leftover space?
- If I flip this to centered symmetry, does it get worse? (If not, the asymmetry wasn't earned.)

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | No visible grid; ad hoc placement; default centering throughout. |
| 4–5 | A grid exists but is broken frequently without reason. |
| 6–7 | Consistent alignment system; composition reads as intentional. |
| 8–9 | Composition has evident architecture; asymmetry used with confidence. |
| 10 | The layout feels inevitable — no other arrangement seems possible. |

### Revision heuristics
- If a layout feels generic: break centered symmetry deliberately in one dimension (not all).
- If it feels chaotic: reduce the number of alignment points, not the number of elements.
- If it feels empty: increase scale of what's there before adding new elements.

---

## 4. Grid & Structure

### Why it matters
The grid is invisible scaffolding. Viewers never see it, but they feel its absence instantly as disorganization or its overuse as rigidity.

### Principles
- A grid should be strict enough to create order and loose enough to allow surprise.
- Column structures should reflect content logic (e.g., three parallel ideas = three columns), not arbitrary division.
- Breaking the grid is a rhetorical device — it should happen rarely and always to draw attention to the one thing that breaks it.

### Best practices
- Define a baseline grid or module and snap type and image edges to it.
- Use the same underlying grid across a system's formats even when column counts change (e.g., 12-col web collapsing predictably to 4-col mobile).
- Reserve grid-breaking (bleeding an image, overlapping a headline across columns) for the single most important moment in a sequence.

### Common mistakes
- A different ad hoc grid on every slide/screen of the same deck or site.
- Overly rigid grids that force awkward wrapping or orphaned words.
- Grid-breaking used so often it stops reading as intentional.

### Anti-patterns
- Visible misalignment between recurring elements (headers, footers, logos) across a sequence — the fastest tell of low craft.
- Grids borrowed from a template that don't match the actual content's logical divisions.

### Observable signals of quality
- Recurring chrome (headers, footers, page numbers, logos) sits in the exact same position, pixel for pixel, across every instance.
- Column counts and gutters are consistent within a given format across the entire piece.

### Reviewer questions
- Does every recurring element (header, footer, nav, logo) occupy identical coordinates everywhere it appears?
- Is the column logic mapped to the content's actual structure (parallel ideas, sequential steps, hierarchy)?
- Where the grid is broken, is it obviously the most important moment in the piece?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | No consistent grid; recurring elements shift position between instances. |
| 4–5 | Grid exists but inconsistently applied. |
| 6–7 | Grid consistently applied; occasional unjustified breaks. |
| 8–9 | Grid invisible but evidently governs everything; breaks are rare and purposeful. |
| 10 | Grid becomes structural storytelling — its logic mirrors the content's logic. |

### Revision heuristics
- If recurring elements drift: audit and lock their coordinates as a template before anything else.
- If the piece feels rigid: identify the single most important slide/screen and permit it — only it — to break the grid.

---

## 5. White Space & Density

### Why it matters
White space is a pacing device. It tells the viewer when to slow down, when to breathe, and where one idea ends and another begins. Density (or its absence) communicates confidence — cramped work reads as anxious; over-empty work reads as thin.

### Principles
- White space should group, not just decorate — proximity determines perceived relationship.
- Density should match content weight: a single powerful statement earns a mostly-empty canvas; a data-dense screen earns a tighter grid, not clutter.
- Consistent spacing units (not one-off gaps) create rhythm.

### Best practices
- Use greater space *between* unrelated groups than *within* a related group — this alone creates instant perceived organization (proximity principle).
- Let hero statements/manifesto lines occupy disproportionate empty space; let reference/utility content sit tighter.
- Establish a spacing scale (e.g., 4 or 5 step multiples) and never introduce an off-scale gap.

### Common mistakes
- Equal spacing between all elements regardless of relationship, making grouping illegible.
- Padding added reflexively to "make it feel more premium" without a proximity logic.
- Cramming content because "it needs to fit" rather than cutting content.

### Anti-patterns
- A single-sentence manifesto slide crammed into a small text box surrounded by unrelated chrome.
- Dense data screens with generous decorative padding that pushes actual information off-screen or below the fold unnecessarily.

### Observable signals of quality
- Grouping is legible with all text as gray boxes — spacing alone reveals what belongs together.
- The most important message in the piece has the most space around it, not the least.

### Reviewer questions
- Does the gap between unrelated groups exceed the gap within a group, everywhere?
- Is the density on this screen proportional to the significance and information load of its content?
- If I only look at the spacing (ignore the content), can I tell which items are related?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Uniform, arbitrary spacing; no grouping legible from space alone. |
| 4–5 | Some grouping visible; inconsistent application. |
| 6–7 | Clear proximity logic; spacing scale mostly consistent. |
| 8–9 | Space actively paces the reading experience; density matches content weight throughout. |
| 10 | Space itself communicates confidence — the piece could not be more or less dense than it is. |

### Revision heuristics
- If grouping is unclear: widen the gap between groups before touching anything inside a group.
- If a key line feels underpowered: give it more surrounding space before enlarging its type.
- If a screen feels busy: remove content before compressing spacing.

---

## 6. Rhythm & Visual Pacing

### Why it matters
A single strong screen is easy. A sequence — deck, site scroll, campaign — succeeds or fails on rhythm: the pattern of tension and release across time.

### Principles
- Sequences need a pulse: dense/quiet, loud/soft, image/type — alternation prevents monotony and fatigue.
- Repetition builds trust; variation within repetition builds interest. Pure repetition is boring; pure variation is chaotic.
- The most important beat in a sequence should be preceded and followed by comparatively quieter beats, so it reads as a peak.

### Best practices
- Map a sequence's "energy line" before designing individual screens — mark which moments are high-energy (manifesto, hero stat, reveal) versus supporting.
- Alternate structural patterns (full-bleed image → text-only → three-column → full-bleed image) rather than repeating the same template screen after screen.
- Use consistent recurring elements (header strip, footer, numbering) as the "beat" that lets variation read as intentional rather than inconsistent.

### Common mistakes
- Every screen in a deck using the identical template, producing monotony.
- No template consistency at all, producing chaos instead of variation.
- Placing the highest-energy moment adjacent to another high-energy moment, canceling both.

### Anti-patterns
- A 20-slide deck where slides 2 through 19 are visually indistinguishable in structure.
- Climax content (the "big idea," the payoff line) buried mid-sequence with no visual signal that it's the peak.

### Observable signals of quality
- Flipping through the sequence quickly (thumbnail view) shows a visible pattern of variation, not a flat repeat or noise.
- The single most important moment is visually unmistakable at thumbnail size.

### Reviewer questions
- If I view this sequence as thumbnails, can I find the climax without reading anything?
- Where does the sequence risk fatigue — three or more visually identical beats in a row?
- Does variation serve the content's actual peaks and valleys, or is it arbitrary?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Flat repetition or unstructured chaos; no discernible pacing. |
| 4–5 | Some variation present but not mapped to content importance. |
| 6–7 | Clear alternation; climax is identifiable with effort. |
| 8–9 | Rhythm mirrors narrative energy; climax is unmistakable. |
| 10 | The pacing alone tells you the story arc, independent of content. |

### Revision heuristics
- If a sequence feels monotonous: identify 2–3 structural templates and alternate them, keeping recurring chrome constant.
- If a climax doesn't land: quiet the screens immediately before and after it.

---

## 7. Visual Balance

### Why it matters
Balance governs whether a composition feels stable and resolved or unsettled and accidental — independent of symmetry.

### Principles
- Balance is optical weight (size, color intensity, density, contrast) distributed across a composition — not literal geometric symmetry.
- Asymmetric balance (a large quiet mass balanced by a small intense one) is more sophisticated than symmetric balance and is the default at higher craft levels.
- Balance should resolve at the edges of the frame — nothing should feel like it's sliding off unintentionally (bleeds excepted, and those should look intentional).

### Best practices
- Test balance by converting the composition to blurred grayscale "blobs" of weight and checking if it feels stable.
- Use one dominant heavy element balanced by a scattering of lighter ones, rather than two heavy elements fighting.
- Let intentional bleeds (photography running off-frame) create dynamic tension against a stable text block, rather than adding more elements to "balance" it.

### Common mistakes
- Overcorrecting an asymmetric composition into symmetry out of visual anxiety.
- Two large, equally weighted elements placed opposite each other, canceling energy instead of creating it.
- Ignoring how the eye's natural weight bias (upper-left heavier reading start in LTR contexts) interacts with placement.

### Observable signals of quality
- The blur/squint test produces a composition that feels settled, not tipping.
- Nothing in the frame feels accidental or orphaned at a corner or edge.

### Reviewer questions
- Squinting at this, does it feel like it would tip over if it were physical?
- Is the asymmetry (if present) doing work, or is it just off-center without purpose?
- Does any single element feel abandoned or unanchored to the rest of the composition?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Composition feels visibly unstable or randomly symmetric by default. |
| 4–5 | Roughly balanced but with obvious dead zones or overweight corners. |
| 6–7 | Balanced; asymmetry present but safe. |
| 8–9 | Confident asymmetric balance; tension feels intentional and resolved. |
| 10 | Balance itself becomes an expressive device, not just a stability mechanism. |

### Revision heuristics
- If a composition feels heavy on one side: don't add a matching element on the other side — reduce weight on the heavy side or introduce one small, high-contrast counterweight.

---

## 8. Color

### Why it matters
Color carries emotional temperature and hierarchy faster than any other variable, and is the fastest way to look either premium or amateur.

### Principles
- Color should be earned through hierarchy and meaning, not decoration — every use of a non-neutral color should answer "why this, why here."
- Restraint reads as confidence; a broad, undisciplined palette reads as indecision.
- The rarer a strong color is used, the more power each use retains.
- Gradients and vivid accents are a "moment," not a texture — used everywhere, they exhaust their own impact.

### Best practices
- Establish one dominant neutral (background/foundation) and let one or two accent colors carry all emphasis.
- Reserve the most saturated or complex color treatment (multi-stop gradients, brand "hero" colors) for the single highest-priority phrase or moment per piece.
- Ensure color-based emphasis still works if desaturated (i.e., it's reinforcing an existing hierarchy, not creating one from scratch).

### Common mistakes
- Using every brand color on one screen because "it's all approved."
- Gradient text applied to body copy or long passages, killing legibility and diluting the device's power.
- Color chosen for individual screens independently, producing an inconsistent palette across a sequence.

### Anti-patterns
- Rainbow decks — every slide getting a different accent color with no logic tying color to meaning.
- Neon/vivid accents on dense, small-scale text (contrast and legibility failure).

### Observable signals of quality
- A colorblind-simulated or grayscale version of the piece still reads its intended hierarchy.
- Only the single most important idea per piece/sequence carries the boldest color treatment.

### Reviewer questions
- If I strip all color, does the hierarchy survive?
- Is this the most important moment in the piece — is that why it gets the boldest color?
- Could I justify every color choice with a one-sentence reason beyond "brand palette"?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Color applied decoratively with no hierarchy logic; multiple competing accents. |
| 4–5 | A palette exists but is used inconsistently or too liberally. |
| 6–7 | Disciplined palette; accent used with general restraint. |
| 8–9 | Color used sparingly and meaningfully; grayscale test passes. |
| 10 | A single, perfectly placed color moment defines the entire piece's memorability. |

### Revision heuristics
- If a piece feels chaotic: cut accent color use to the single most important element and make everything else neutral.
- If a piece feels flat: don't add more color — increase the contrast/saturation of the one accent already present.

---

## 9. Photography & Imagery

### Why it matters
Imagery sets emotional register instantly and, more than any other element, signals production value (or its absence).

### Principles
- Photography must earn its scale — hero-sized images require hero-quality content, composition, and resolution.
- Consistency of treatment (color grade, cropping logic, subject distance) across a set matters more than any single image's individual quality.
- Imagery should support the message's emotional tone, not merely illustrate the literal subject ("stock photo of people pointing at a laptop" problem).

### Best practices
- Establish a consistent crop ratio and treatment (grade, contrast, saturation) system-wide.
- Use one clear "hero" image logic per format (e.g., always bleeds off one edge, always same corner) so the pattern itself becomes a brand signal.
- Prefer a smaller number of genuinely strong images over a larger number of mediocre ones.

### Common mistakes
- Mixing incompatible photographic styles (candid documentary next to polished studio) within the same sequence.
- Low-resolution or awkwardly cropped images used because "it's the only shot available."
- Generic stock imagery that could belong to any brand in any industry.

### Anti-patterns
- Photos of people performing exaggerated "candid" gestures for the camera (fake enthusiasm).
- Decorative images added purely to fill empty space rather than to communicate.

### Observable signals of quality
- Every image in a set could plausibly belong to the same shoot/era/treatment.
- Removing the caption/context, a viewer still senses the intended emotional tone from the image alone.

### Reviewer questions
- Would this specific image work for a direct competitor's brand with a text swap? If yes, it's too generic.
- Is the crop/treatment consistent with every other image in this set?
- Does this image's emotional register match the words next to it?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Generic stock imagery, inconsistent treatment, filler use. |
| 4–5 | Serviceable imagery, inconsistent system across the set. |
| 6–7 | Strong, consistent treatment; imagery supports message. |
| 8–9 | Imagery is distinctive enough to be recognizable as this brand's, tonally precise. |
| 10 | The image and message are inseparable — imagery becomes the idea. |

### Revision heuristics
- If imagery feels generic: replace literal illustration with tonal/textural imagery that evokes feeling instead of depicting the subject directly.
- If a set feels inconsistent: unify crop ratio and color grade before replacing any individual image.

---

## 10. Illustration & Iconography

### Why it matters
Illustration and icons are used when photography can't express an abstract idea. Poor execution here is one of the fastest ways to look unfinished or "corporate clip-art."

### Principles
- Illustration style must be singular and systemic — one line weight, one corner radius logic, one level of detail — applied everywhere.
- Icons should communicate at a glance without a label; if a label is always required, the icon has failed.
- Illustration should be reserved for genuinely abstract concepts that photography cannot represent — not used as decoration to avoid harder photographic or typographic solutions.

### Best practices
- Build icon sets from a shared underlying grid and stroke weight so they feel like one family even when depicting unrelated concepts.
- Keep illustrative detail proportional to display size — simplify aggressively at small sizes.
- Treat brand marks/logos as fixed assets; never redraw or reinterpret them per-instance.

### Common mistakes
- Mixing icon styles (filled and outlined, rounded and sharp) within the same set.
- Illustration used to avoid the harder work of finding the right words or the right photograph.
- Overly literal icons for abstract concepts (a brain icon for "smart," a rocket for "growth") — cliché defaults.

### Anti-patterns
- Free stock icon packs mixed together without normalization.
- Illustration so detailed it fails to reproduce legibly at intended display size.

### Observable signals of quality
- Every icon in a set could be identified as belonging to that set with the label removed.
- No icon relies on a cliché metaphor.

### Reviewer questions
- Do all icons in this set share the same stroke weight, corner logic, and level of detail?
- Is this icon/illustration solving a problem type couldn't solve better?
- Is this a cliché visual metaphor being used because a better one wasn't found?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Mismatched styles, cliché metaphors, inconsistent weight. |
| 4–5 | Single style but generic/cliché concepts. |
| 6–7 | Consistent system, competent execution. |
| 8–9 | Distinctive style, original metaphors, flawless consistency. |
| 10 | The illustration system itself becomes a recognizable brand asset. |

### Revision heuristics
- If icons feel inconsistent: normalize stroke weight and grid before changing any individual icon's concept.
- If a metaphor feels cliché: ask what this concept looks like that has never been drawn before.

---

## 11. Motion

### Why it matters
Motion is punctuation for interfaces and video — it should clarify cause and effect and direct attention, not perform for its own sake.

### Principles
- Motion must have a functional reason (reveal hierarchy, show relationship, provide feedback) — decoration-only motion reads as noise.
- Easing and timing should feel physical (accelerate/decelerate naturally) rather than linear or robotic.
- Consistency of timing/easing curves across an experience matters more than any single animation's cleverness.

### Best practices
- Default to short durations (150–400ms for UI feedback; longer, deliberate durations for narrative/brand moments) and consistent easing curves system-wide.
- Animate to reveal relationships (this caused that) rather than to decorate an otherwise static layout.
- Respect reduced-motion preferences; ensure motion is additive, not load-bearing, for comprehension.

### Common mistakes
- Every element entering with the same generic fade/slide regardless of relationship or importance.
- Motion so slow or elaborate it delays the user from their goal.
- Inconsistent easing curves across a single experience, making it feel unpolished.

### Anti-patterns
- Motion used to mask weak layout (spinning/bouncing content that would look bad if it simply appeared).
- Parallax or effects applied because they're available, not because they clarify anything.

### Observable signals of quality
- Turning motion off, the interface/story still fully makes sense — motion is enhancement, not scaffolding.
- Every animated transition can be explained with "this shows X causing Y."

### Reviewer questions
- What would break if this motion were removed?
- Does the timing feel physical, or does it feel like a default template animation?
- Is this motion decorating a layout that doesn't work statically?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Default/template animations with no functional logic. |
| 4–5 | Some functional motion, inconsistent timing/easing. |
| 6–7 | Motion consistently supports comprehension; timing feels considered. |
| 8–9 | Motion clarifies relationships the static layout alone couldn't. |
| 10 | Motion becomes an inseparable part of the brand's expression. |

### Revision heuristics
- If motion feels gratuitous: remove it and check if the static state still communicates; if yes, motion wasn't earning its place.
- If timing feels off: standardize on one easing curve and duration scale across the whole experience before tweaking individual animations.

---

## 12. Storytelling & Narrative Structure

### Why it matters
Design without narrative structure is decoration. Every deck, site, and campaign is an argument moving toward a conclusion — structure determines whether that argument lands.

### Principles
- Every piece should be able to state its argument in one sentence before design begins ("we believe X, therefore Y").
- A story needs tension (a problem, a stake, a contrast) — pure feature listing is not a narrative.
- Payoff moments must be earned by what precedes them; a manifesto line without setup is just a slogan.

### Best practices
- Map the narrative arc (setup → tension → turn → resolution) before laying out any single screen.
- Use structural contrast (calm exposition vs. bold declaration) to physically mark narrative beats.
- End on the idea you most want remembered, not on the least controversial summary.

### Common mistakes
- Front-loading all information with no build, so nothing feels like a "reveal."
- A closing statement that restates the opening without adding insight or resolution.
- Treating a sequence as a list of unconnected facts rather than a built argument.

### Anti-patterns
- Generic, brand-agnostic mission statements as the "big idea" (interchangeable with any competitor's).
- A climax buried in the middle of the sequence rather than positioned for maximum impact.

### Observable signals of quality
- A reader can restate the piece's core argument in one sentence after seeing only the headlines/beats.
- The final beat feels different in register from the opening beat — something changed.

### Reviewer questions
- Can I state this piece's argument in one sentence?
- What is the tension being resolved — and would I feel its absence if it were removed?
- Does the ending earn its emphasis, or could it appear anywhere in the sequence unchanged?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | No discernible argument; a list of disconnected facts. |
| 4–5 | An argument exists but is thin or generic. |
| 6–7 | Clear, specific argument with basic build. |
| 8–9 | Genuine tension and payoff; the ending feels earned. |
| 10 | The structure itself makes the argument feel inevitable and memorable. |

### Revision heuristics
- If a piece feels flat: identify what's actually at stake and restructure around that tension, not the client's org chart of facts.
- If the ending feels weak: cut it back to the single sharpest sentence in the piece and build backward from there.

---

## 13. Information Architecture

### Why it matters
IA determines whether people can find and process what they need without conscious effort. Poor IA makes even beautifully styled work feel confusing.

### Principles
- Group by relationship to the user's task or question, not by internal organizational structure.
- The number of top-level categories should stay within short-term memory limits (roughly 5–9, ideally fewer).
- Every piece of content should have exactly one obvious "home."

### Best practices
- Card-sort or outline content by what a first-time user is trying to accomplish, before designing any screen.
- Use progressive disclosure: show the minimum needed to make the next decision, defer detail.
- Label sections in the audience's language, not internal jargon.

### Common mistakes
- Navigation/section structure that mirrors internal company departments rather than user goals.
- Duplicate or ambiguous entry points to the same content.
- Overloading a single screen because "it's all related" without a clear task boundary.

### Anti-patterns
- Mega-menus or slide decks with 15+ equally-weighted top-level sections.
- Critical information buried several levels deep because it wasn't a priority internally.

### Observable signals of quality
- A first-time user can predict where to find something before clicking/turning the page.
- No two sections compete for the same content or question.

### Reviewer questions
- Would a first-time visitor describe these categories the same way we do?
- Is there a single, unambiguous home for every major idea in this piece?
- Are we organizing by what we make, or by what the audience is trying to do?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Organization mirrors internal structure; no clear user task logic. |
| 4–5 | Some task logic present but categories overlap or are too numerous. |
| 6–7 | Clear, task-based structure; minor ambiguity. |
| 8–9 | Structure is intuitive enough to need no explanation. |
| 10 | The architecture disappears entirely — content simply feels "where it should be." |

### Revision heuristics
- If users seem lost: reduce the number of top-level choices before redesigning any individual screen.
- If categories overlap: merge them and re-test rather than adding disambiguating labels.

---

## 14. User Attention & Focus

### Why it matters
Attention is finite and the first casualty of poor design. Every unnecessary demand on attention is a tax the message pays.

### Principles
- Every screen should have exactly one primary call to attention; everything else is secondary or supporting.
- Attention should be spent proportionally to importance — busywork should never outcompete the message for visual energy.
- Distraction is any element competing with the primary focus without earning that competition.

### Best practices
- Identify and eliminate secondary elements that visually compete with the primary CTA/message (competing color, competing motion, competing size).
- Use visual quiet immediately around the most important element (the "halo" of empty space) to protect it from competition.
- Sequence multiple asks (e.g., multiple CTAs) rather than presenting them simultaneously with equal weight.

### Common mistakes
- Multiple CTAs of identical visual weight on one screen.
- Decorative animation or imagery running concurrently with a moment that requires focused reading.
- Notification/badge-style elements that hijack attention from the primary task.

### Anti-patterns
- "Everything is clickable and colorful" screens where no single action reads as primary.
- Autoplaying motion behind body copy the user is meant to read.

### Observable signals of quality
- Eye-tracking or simple observation shows first attention lands on the intended element consistently across viewers.
- Secondary elements are visibly, deliberately quieter than the primary focus.

### Reviewer questions
- If a user has 3 seconds, what should they do — and is that the only obvious action available?
- What is competing with the primary focus for attention right now, and does it deserve to?
- Is anything moving, blinking, or colorful near content that requires quiet focus?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | No clear primary action; multiple competing elements of equal weight. |
| 4–5 | Primary action identifiable but weakly differentiated. |
| 6–7 | Clear primary focus; minor competing elements. |
| 8–9 | Attention flow is fully controlled and effortless. |
| 10 | The experience directs attention so precisely it feels like it's reading the user's mind. |

### Revision heuristics
- If attention scatters: reduce the number of simultaneous asks to one per screen/moment.
- If a CTA underperforms visually: quiet its surroundings before enlarging the CTA itself.

---

## 15. Interaction Design

### Why it matters
Interaction is where design meets behavior. It determines whether an interface feels responsive and trustworthy or effortful and uncertain.

### Principles
- Every interactive element must give immediate, legible feedback (state change) on interaction.
- Interactive affordance should be visually honest — things that look clickable should be clickable, and vice versa.
- Consistency of interaction pattern across a product matters more than the cleverness of any single interaction.

### Best practices
- Define hover/active/focus/disabled states for every interactive element before shipping any single screen.
- Keep interaction cost proportional to task frequency — reduce friction most on the most common actions.
- Make errors recoverable and clearly explained, not just flagged.

### Common mistakes
- Interactive elements with no visible state change on hover/press.
- Non-interactive elements styled in ways that imply interactivity (false affordance).
- Inconsistent interaction patterns for the same action type across a product (e.g., three different ways to dismiss a modal).

### Anti-patterns
- Custom-styled form controls that break native accessibility/keyboard behavior without compensating.
- "Mystery meat" navigation requiring hover to reveal what something is or does.

### Observable signals of quality
- Every clickable element provides feedback within 100ms of interaction.
- A new user can complete the primary task without instruction.

### Reviewer questions
- Does everything that looks clickable behave as clickable, and nothing else?
- Is the same type of action handled identically everywhere it appears in this product?
- What happens when something goes wrong — is recovery clear?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | No consistent feedback states; false or missing affordances. |
| 4–5 | Basic feedback present, inconsistent across the product. |
| 6–7 | Consistent, clear interaction patterns throughout. |
| 8–9 | Interaction feels immediate and trustworthy at every touchpoint. |
| 10 | Interaction is so well-calibrated it becomes invisible — the product simply "does what you'd expect." |

### Revision heuristics
- If interaction feels untrustworthy: audit for missing feedback states before adding new interaction patterns.
- If a flow feels effortful: measure clicks/taps to task completion and cut steps before restyling.

---

## 16. Brand Expression

### Why it matters
Brand expression is what makes work identifiably "this company's" rather than a template any competitor could reskin. This is the difference between decoration and identity.

### Principles
- A brand's expression should be recognizable with the logo removed.
- Every brand touchpoint should express the same underlying idea through different tools (a strategic idea expressed in type, in motion, in tone — not just a locked-down visual kit).
- Genuine brand expression sacrifices something (a color, a convention, a safe choice) to gain distinctiveness — brands that try to appeal to everyone visually differentiate to no one.

### Best practices
- Define the brand's expression as a strategic idea first ("we believe X"), then translate that idea across every medium independently rather than copy-pasting one visual template.
- Identify and protect the 2–3 signature moves (a typographic habit, a compositional tendency, a tone of voice) that most reliably signal "this is us."
- Pressure-test distinctiveness by swapping the logo for a competitor's — if the piece still works, it isn't sufficiently branded.

### Common mistakes
- Brand expression reduced to "use the approved colors and font" with no deeper idea behind the choices.
- Visual identity so safe/generic it could belong to any company in the category.
- Inconsistent expression of the same underlying idea across formats.

### Anti-patterns
- Category clichés adopted uncritically (e.g., every fintech brand using the same blue-and-white "trustworthy" palette).
- A brand system so rigid it produces monotony rather than recognizability.

### Observable signals of quality
- The logo-swap test fails — the piece clearly doesn't work for a competitor.
- A viewer familiar with the brand can identify it from a cropped, logo-free fragment.

### Reviewer questions
- If I remove the logo, does this still look like nobody else?
- What is the one idea this brand believes that a competitor doesn't — is it visible here?
- Is this choice safe because it's smart, or safe because it's easy?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Generic, category-default; logo-swap test fails completely. |
| 4–5 | Some brand elements present but expression is shallow (color/logo only). |
| 6–7 | Recognizable expression across most touchpoints. |
| 8–9 | Distinctive, consistent expression of a real strategic idea. |
| 10 | The work becomes a reference point that competitors start imitating. |

### Revision heuristics
- If a piece feels generic: identify the category default and deliberately move away from it in one dimension.
- If expression feels inconsistent across formats: articulate the underlying idea in one sentence and re-derive each format from that sentence rather than from the other formats.

---

## 17. Editorial Quality

### Why it matters
Editorial quality is the discipline of a publication: every word and image is there because it was chosen, not because it was available. It is the difference between a document and a design.

### Principles
- Every sentence should be edited for the fewest words that carry full meaning.
- Content and layout should be co-authored, not sequential (design should never be "filling in" copy written elsewhere with no visual consideration, and vice versa).
- A ruthless edit ("what can we cut") should occur after every draft.

### Best practices
- Read all copy aloud; anything that isn't clear when spoken needs revision.
- Apply a consistent editorial voice (sentence length, tone, punctuation habits) across an entire piece or campaign.
- Caption and label everything with precision — vague labels ("Learn More," "Solutions") are an editorial failure, not just a UX one.

### Common mistakes
- Copy written in isolation from layout, resulting in awkward line breaks or orphaned words.
- Marketing jargon and buzzwords standing in for a specific, differentiated claim.
- Headlines that describe a category ("Innovative Solutions") rather than make a claim.

### Anti-patterns
- Lorem-ipsum-brain: copy that could be swapped for any competitor's without losing meaning.
- Walls of unedited text where a single distilled sentence would do more work.

### Observable signals of quality
- Every headline makes a specific, falsifiable claim rather than a vague aspiration.
- Reading the copy alone (no design) still sounds crafted, distinct, and intentional.

### Reviewer questions
- Could this exact sentence appear in a competitor's materials unchanged? If yes, rewrite it.
- What's the fewest words this idea could be said in without losing meaning?
- Is this word here because it's precise, or because it's a habit?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Generic copy, unedited length, no distinct voice. |
| 4–5 | Some editing evident but voice is inconsistent or vague. |
| 6–7 | Clear, edited voice; occasional generic phrasing. |
| 8–9 | Every line is deliberate, distinct, and precise. |
| 10 | The copy alone, without any design, would be worth publishing. |

### Revision heuristics
- If copy feels generic: replace category language ("innovative," "seamless," "cutting-edge") with a specific, falsifiable claim.
- If a piece feels wordy: cut by a third, then read aloud again.

---

## 18. Presentation Craft

### Why it matters
Presentation craft is the layer of finishing detail that separates professional work from amateur work at close inspection — pixel-precision, consistency, and polish.

### Principles
- Craft is invisible when present and glaring when absent — the goal is that nothing draws attention to a mistake.
- Small inconsistencies compound: a 2px misalignment repeated 20 times reads as systemic sloppiness.
- The final 10% of polish (kerning, optical alignment, file/export quality) takes disproportionate care and is the actual signature of professionalism.

### Best practices
- Do a dedicated "craft pass" separate from the "concept pass" — review purely for alignment, spacing consistency, color consistency, and typos.
- Zoom to 200%+ on any piece before final delivery to catch pixel-level misalignment.
- Maintain a consistent export/production quality standard (resolution, color profile, file naming) across every deliverable in a set.

### Common mistakes
- Shipping with unreviewed default spacing/kerning from source software.
- Inconsistent corner radii, stroke weights, or shadow values across a set that should match.
- Typos or inconsistent capitalization/punctuation style across a sequence.

### Anti-patterns
- Visibly different logo sizes/placements across a "consistent" template.
- Compression artifacts, low-res assets, or stretched/distorted images shipped as final.

### Observable signals of quality
- Zooming into any two "identical" recurring elements shows pixel-level identical placement.
- Zero typos, consistent punctuation and capitalization style, on a full read-through.

### Reviewer questions
- Have I done a pass looking only for alignment and spacing errors, separate from judging the concept?
- Would this survive being projected on a 20-foot screen or printed at full size?
- Is every recurring element (logo, header, footer, numbering) pixel-identical across every instance?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Visible misalignment, typos, inconsistent recurring elements. |
| 4–5 | Mostly clean but with detectable inconsistencies on close inspection. |
| 6–7 | Clean at normal viewing distance; minor issues at close zoom. |
| 8–9 | Flawless at any zoom level; every recurring element matches exactly. |
| 10 | Craft is so precise it becomes part of the brand's credibility. |

### Revision heuristics
- If something feels "almost right": it's likely a 1–4px alignment or spacing error — audit with guides before redesigning.
- Always run a dedicated typo/consistency pass as the very last step before delivery, never combined with concept revisions.

---

## 19. Accessibility

### Why it matters
Design that only works for some of its audience isn't finished design. Accessibility is also a leading indicator of overall craft — teams that ignore it tend to have skipped rigor elsewhere too.

### Principles
- Legibility and usability for people with visual, motor, cognitive, or situational impairments is a baseline requirement, not an enhancement.
- Accessible design is very often simply better design for everyone (higher contrast, clearer hierarchy, larger touch targets benefit all users).
- Compliance (e.g., WCAG contrast ratios) is a floor, not a design goal in itself.

### Best practices
- Check color contrast ratios for all text against its background (minimum 4.5:1 for body text, 3:1 for large text, as a baseline standard).
- Never encode meaning in color alone (e.g., red/green status) — pair with icon, label, or pattern.
- Ensure touch targets meet minimum size standards and interactive elements are keyboard-navigable.
- Provide meaningful alt text and structural markup (headings, landmarks) for non-visual navigation.

### Common mistakes
- Low-contrast "elegant" gray-on-white or white-on-pastel text that fails baseline contrast.
- Critical information conveyed only through color or only through hover-reveal.
- Decorative motion with no reduced-motion accommodation.

### Anti-patterns
- Text embedded in images with no alt text or transcript equivalent.
- Interactive elements too small or too close together for reliable use.

### Observable signals of quality
- Automated contrast/accessibility audit tools return no critical errors.
- The piece remains fully comprehensible with color removed and with motion disabled.

### Reviewer questions
- Does every text/background pairing meet baseline contrast standards?
- If color were removed entirely, would any meaning be lost?
- Can this be navigated and understood without a mouse, and without sight?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Multiple contrast failures; meaning encoded only in color; no keyboard/alt support. |
| 4–5 | Some accommodations present, inconsistent application. |
| 6–7 | Meets baseline standards throughout. |
| 8–9 | Accessible by default; accessibility considerations are invisible because they're built in. |
| 10 | Accessibility and aesthetic quality are fully unified — the accessible version is also the most beautiful version. |

### Revision heuristics
- If contrast fails: darken/lighten the text or background rather than changing the hue, to preserve palette intent.
- If meaning relies on color: add a redundant signal (icon, label, pattern) rather than removing the color.

---

## 20. Overall Taste & Sophistication

### Why it matters
This is the section that resists a formula and matters most. Taste is the accumulated judgment that knows when to break every rule above — and is the actual differentiator between "correct" and "exceptional" work.

### Principles
- Restraint is usually the mark of sophistication; the ability to do less, better, is harder than doing more.
- The most sophisticated choice is often the one that looks effortless and takes the most iterations to arrive at.
- Confidence reads visually: fewer decisions, made more decisively, outperform many tentative decisions.
- Taste is trained by exposure to work outside the client's category (architecture, editorial, industrial design, film) — not by studying more of the same category.

### Best practices
- Ask "what would we cut if we had to remove 20% of this piece" — and then seriously consider doing it.
- Study reference work with no obvious surface resemblance to the current brief (a Muji product, a Pentagram identity, an Apple keynote) and extract the underlying principle rather than the surface style.
- Prefer the choice that requires more nerve over the choice that requires more decoration.

### Common mistakes
- Mistaking more decoration, more color, more motion for more sophistication.
- Defaulting to trend-of-the-moment aesthetics without evaluating fit to the specific brand and message.
- Confusing "safe" with "correct" — sophistication often requires a defensible risk.

### Anti-patterns
- Design-by-committee outputs where every stakeholder's preference was accommodated, diluting a single point of view.
- Trend-chasing (glassmorphism, brutalism, whatever is currently popular on design Twitter) applied without regard to brand fit.

### Observable signals of quality
- The piece has a clear point of view that a knowledgeable viewer could defend even if they personally disagreed with a choice.
- Nothing in the piece feels like it's there to please a stakeholder rather than to serve the work.
- The work would still look distinctive and confident five years from now, not just on trend today.

### Reviewer questions
- If we removed 20% of this, would it be better or worse?
- Whose preference does this specific choice serve — the work's, or a stakeholder's?
- Will this look considered in five years, or will it look like "2026"?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Committee-diluted, trend-chasing, or purely decorative; no clear point of view. |
| 4–5 | A point of view exists but is inconsistently held or overly cautious. |
| 6–7 | Confident point of view, competent execution, occasional safe choices. |
| 8–9 | Distinctive, restrained, evidently the product of many cuts and hard decisions. |
| 10 | The work sets a new reference point rather than following one. |

### Revision heuristics
- If work feels average: identify what was added to please someone rather than to serve the idea, and remove it.
- If work feels safe: identify the boldest version considered and ask why it was rejected — revisit that reason critically.

---

## 21. Cross-Format Consistency

### Why it matters
Most client engagements span decks, sites, campaigns, and social — a rubric that only judges single artifacts misses whether the *system* holds together across formats and time.

### Principles
- A system should feel like one voice speaking in different rooms — not one costume worn by different voices.
- Consistency is expressed through underlying logic (hierarchy rules, spacing scale, narrative tone), not through literally identical layouts across incompatible formats.
- A system is only proven once it's been stress-tested on a format it wasn't originally designed for.

### Best practices
- Define the underlying rules (hierarchy logic, spacing scale, color usage rules, tone of voice) independently of any single format, then adapt each format to those rules.
- Audit a new format against the rubric sections above independently — don't assume consistency because "it uses the same colors."
- Build one exemplar per major format (deck, web, social, motion) early, and use those four as the calibration reference for everything after.

### Common mistakes
- A system that only works in the format it was first designed in (e.g., a beautiful deck that produces an awkward website).
- Literal copy-paste of layout between formats with very different aspect ratios/contexts, rather than adapting the underlying logic.

### Anti-patterns
- Divergent tone of voice between formats (playful social copy vs. stiff corporate deck copy) for the same brand and audience.

### Observable signals of quality
- A viewer shown two different formats (e.g., a slide and a social post) from the same system can identify them as the same brand without seeing a logo.
- New formats can be produced by a different designer and still pass the rubric without additional guidance beyond the underlying rules.

### Reviewer questions
- Does this format hold up as its own excellent piece, or does it only work because it was forced into another format's template?
- Could someone unfamiliar with the brand identify these as the same system across two different formats?

### Scoring rubric (1–10)
| Score | Description |
|---|---|
| 1–3 | Formats feel unrelated; no shared underlying logic. |
| 4–5 | Surface consistency (colors, logo) but underlying logic breaks down per format. |
| 6–7 | Consistent underlying logic; some formats feel forced. |
| 8–9 | Every format feels native to its medium while clearly the same system. |
| 10 | The system generates new, excellent formats without additional creative direction. |

### Revision heuristics
- If a new format feels off-brand: check whether the underlying rules were adapted to the format's native constraints, or literally copied from another format.

---

## Appendix A — Universal vs. JMS-Calibrated vs. Future-Exemplar Principles

### Universal (apply regardless of brand, era, or category — not open to house-style debate)
- Sections 1–8 (Typography, Hierarchy, Layout/Composition, Grid, White Space, Rhythm, Visual Balance, Color) — these encode long-standing print/editorial/graphic design principles independent of any brand aesthetic.
- Sections 13–15 (Information Architecture, Attention, Interaction) — grounded in cognitive/HCI research, not stylistic preference.
- Section 19 (Accessibility) — non-negotiable baseline.
- Section 17 (Editorial Quality) — precision and economy of language are universal craft standards.

### Requires JMS calibration (the *principle* is durable; the *threshold/example* should be tuned as JMS produces more reference work)
- Section 16 (Brand Expression) — "signature moves" that define JMS's own point of view need to be identified from a growing body of work, not just from clients' brands.
- Section 20 (Overall Taste) — the specific reference points (which studios, which projects) JMS holds up as exemplars should evolve as JMS builds its own canon.
- Section 6 (Rhythm/Pacing) — ideal sequence lengths and alternation patterns may differ for JMS's typical formats (long B2B decks vs. campaign sequences) and should be recalibrated against JMS's actual output volume.
- Section 21 (Cross-Format Consistency) — the specific "four exemplar formats" to calibrate against should be selected once JMS has strong examples in each.

### Will require future exemplar projects to fully specify
- Concrete scoring anchors (what does an actual "8" vs "6" JMS deck slide look like, side by side) — this rubric currently defines the criteria; a future version should attach 2–3 real annotated examples per section at each score band.
- A "JMS signature move" library (Appendix B, to be built) — the 5–10 recurring craft decisions across JMS's best work that should be taught to every new designer as house habits, not universal law.
- Category-specific calibration (a B2B enterprise brand deck and a consumer DTC launch site may reasonably score differently on "Density" and "Color" while both scoring a 9 on Taste) — needs real cross-category examples to define acceptable variance.

### Can become automated / AI-scored criteria (near-term)
- Typography: type-level count, contrast ratios, line-length compliance, tracking/leading against a defined scale.
- Grid: pixel-diff auditing of recurring elements (headers, footers, logos) across a sequence for exact positional consistency.
- Color: palette extraction and count, contrast ratio checks (WCAG), grayscale-hierarchy-preservation test (programmatic desaturation + edge/contrast detection).
- Accessibility: fully automatable today via existing contrast/audit tooling (axe, Lighthouse, WCAG scanners).
- White Space/Density: spacing-scale-compliance checks (are all gaps multiples of the defined unit?).
- Cross-Format Consistency: automated detection of shared design tokens/rules usage across a file set.

### Will remain human/AI-judgment calls, not fully automatable, for the foreseeable future
- Storytelling & Narrative Structure (requires understanding of meaning and stakes, not just structure).
- Brand Expression and Overall Taste (require comparative cultural/category judgment).
- Photography/Illustration tonal fit (requires understanding emotional register, not just style-matching).

---

*End of JMS Design Rubric v1.0. This document is intended to be revised as JMS's own body of work grows — treat every "8" or above piece of delivered work as a candidate to add to Appendix B in future versions.*
