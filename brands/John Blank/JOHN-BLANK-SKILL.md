# John Blank Skill

Use this skill for any showroom, activation, pop-up, retail-adjacent, event, or branded spatial concept in this Project.

## Core Rule

**The real John Blank space is the source of truth.**

Do not invent a larger, deeper, taller, cleaner, or more idealized room than the actual space. Client concepts change; the architecture does not.

## 1. Fixed John Blank Measurements

Use these dimensions for the **front room**:

- **Width:** approximately **14′4″**
- **Depth:** approximately **29′5″**
- **Ceiling height:** approximately **14′**

These dimensions come from the John Blank room reference used in the ALSO experience guide.

### Measurement rules

- Preserve the real width-to-depth ratio in every interior concept.
- Do not visually stretch the room, widen the walls, raise the ceiling, or create extra depth to accommodate an idea.
- Preserve real openings, columns, doors, windows, ceiling structure, steps, sightlines, and circulation.
- Keep people, furniture, products, displays, and installations at believable scale.
- If a generated image feels more spacious than the source room, **fix the architecture first**.
- Treat these measurements as the standing front-room reference unless Michael provides newer measured drawings.

## 2. Required Spatial Reference Images

These are the **canonical John Blank source images**. Use them every time the relevant view is being designed. Do not substitute a generic gallery, showroom, storefront, or AI-invented room.

All canonical references live in [`assets/reference-images`](./assets/reference-images/). Read the [reference-image README](./assets/reference-images/README.md) for the full measurement record, architectural constraints, and unresolved area discrepancy. The front-room dimensions above are approximate; do not treat them as a verified survey.

Preserve the documented three broad steps connecting the front room to the raised wood gallery, whose ceiling is approximately 12′ high. Do not flatten this level change. Preserve the single continuous storefront bay and the exterior elements documented in the README.

### Interior

- [Interior — closed/front-room reference](./assets/reference-images/johnblank-inside-closed.jpg) — Primary reference for the actual room depth, ceiling, walls, openings, steps, and architectural constraints.
- [Interior — open reference](./assets/reference-images/johnblank-inside-open.jpg) — Primary reference for understanding the relationship between the front room and the adjoining space.

### Exterior

- [Exterior — primary storefront reference](./assets/reference-images/johnblank-front.jpg) — Primary reference for storefront architecture, opening, facade proportions, and exterior concepts.
- [Linden Street — straight-on reference](./assets/reference-images/photo-linden-front.jpg) — Use for accurate storefront context, facade bounds, and street-facing concepts.
- [Linden Street — left view](./assets/reference-images/photo-linden-left.jpg) — Use for neighboring architecture, sidewalk context, and oblique views toward the left.
- [Linden Street — right view](./assets/reference-images/photo-linden-right.jpg) — Use for neighboring architecture, sidewalk context, and oblique views toward the right.

### Required image-input workflow

- Visually inspect the relevant real photographs, choose one as the base view, and pass its actual image data to the image-editing or reference-image tool. Supply supporting photographs when the tool supports them. A filename, Markdown link, or text description alone does not mean the generator has received the image.
- State which photographs were inspected and which were supplied to the generator. Do not claim either step occurred unless it did.
- If the environment cannot retrieve or supply the photographs, ask Michael to attach the relevant images before making a site-specific render. If he chooses to proceed without them, label the result as a conceptual mood study with unverified architecture.
- For a faithful visualization, edit the source photograph while retaining its camera position, perspective, openings, structural elements, room boundaries, and floor levels. Fit graphics, furnishings, lighting, and temporary installations within that space.

### How to use the references

- For an **interior concept**, start from the linked interior photography and preserve its architecture, room proportions, ceiling structure, wall positions, steps, openings, and camera logic.
- For an **exterior concept**, start from the linked storefront photography and preserve the real facade, opening, wall bounds, tree, utility pole, sidewalk relationship, and neighboring architecture.
- A generated concept image is **not** an architectural reference. Always return to these source images when proportions drift.
- Do not extend graphics, structures, displays, or architecture beyond physical surfaces that exist in the source photography.
- For a different camera angle, prefer a real photograph from that view. If none exists, use multiple source photographs and available drawings to constrain it, and label the new view as an inferred perspective with unverified geometry.

## 3. John Blank / JMS Spatial Style

The visual language should feel:

- Bold
- Graphic
- Large-scale
- Minimal but high-impact
- Experiential rather than conventionally retail
- Confident, not over-designed

### Default moves

- Oversized wall coverings
- Large-format photography or artwork
- Full-wall graphics rather than small framed moments
- Strong floor graphics when appropriate
- One or two memorable physical interventions
- Large brand gestures with restrained secondary details
- Product integrated into the environment rather than displayed like a standard store
- People used for scale, energy, and realism
- A strong visual idea that can be understood from the street

### Avoid

- Small decorative graphics everywhere
- Generic shelving systems dominating the room
- Trade-show-booth aesthetics
- Too many signs, headlines, or invented slogans
- Overly polished luxury-retail styling unless the client calls for it
- Empty oversized rooms that ignore the real footprint
- Architecture that changes from concept to concept

## 4. Concept Hierarchy

When developing a spatial image, prioritize in this order:

1. Real John Blank architecture and measurements
2. Canonical interior/exterior reference image
3. Client brand assets and approved messaging
4. One strong spatial idea
5. Large graphic treatment
6. Product / activation / furniture
7. People and atmosphere
8. Small details

**Brand expression adapts to the room. The room does not adapt to the brand expression.**

### Reference hierarchy

When references disagree, use this order:

1. Newer confirmed measured drawings or measurements
2. Real canonical reference photography
3. Documented measurements in this skill
4. Client brand assets and project-specific creative direction
5. Previously generated concept imagery

**Generated concept imagery is never architectural source of truth.**

## 5. Copy + Brand Rules

- Use approved client language whenever possible.
- Do not invent campaign slogans unless explicitly asked.
- Prefer brand name, product/category names, existing campaign language, technical information, or no copy at all.
- Let scale, imagery, graphics, material, and spatial composition do most of the work.

## 6. Before Generating Any Image

Check:

- Am I using the **14′4″ × 29′5″ × 14′** front-room reference?
- Did I visually inspect the correct interior or exterior source photographs and supply the selected base photo as an actual image input to the generator?
- Am I preserving the actual proportions and architectural features?
- Does this still clearly feel like John Blank?
- Is the main move bold enough?
- Are the graphics large enough?
- Have I avoided turning it into generic retail?
- Is anything shown physically impossible in the real space?
- Have I accidentally used a previous generated concept as the architectural source?

If any answer is wrong, correct it before generating.

### After generating: verify the architecture

Compare the output with the original base photograph and the reference-image README before delivery. Check storefront opening placement and proportions, apparent room depth, ceiling structure, floor levels and connecting steps when visible, and relevant exterior context. Check furniture and people against the documented scale. A cropped or obscured feature is not proof that it was preserved.

If a major mismatch is visible, revise using the original photograph as the architectural reference. If the tool still cannot preserve the site, disclose the limitation and label the image conceptual rather than presenting it as a faithful John Blank visualization. Do not claim exact dimensional accuracy from a generated perspective.

## 7. Revision Rule

When Michael says to keep an existing concept and change one thing:

**Preserve everything else.**

Do not casually alter:

- room dimensions
- camera angle
- wall graphics
- floor graphics
- central installation
- lighting
- layout
- product placement

unless the requested change requires it.

If there is any conflict between a generated image and the real John Blank references, **the real references win**.

## Invocation

Michael can say:

**“Use the John Blank Skill.”**

That means:

Read the documented John Blank measurements and uncertainties, inspect and supply the relevant real photographs as image inputs, preserve and check the true architecture, and apply the bold John Blank/JMS large-format spatial language defined above.
