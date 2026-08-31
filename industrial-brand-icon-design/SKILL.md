---
name: industrial-brand-icon-design
description: Use when designing, generating, simplifying, or revising branded industrial functional icons for automotive, heavy-duty truck, diagnostic-tool, battery-testing, Amazon A+, banner, feature-card, parameter, or system-diagnostic projects.
---

# Industrial Brand Icon Design

## Overview

Build a reusable brand icon system, not isolated illustrations.

**First glance: identify the object. Second glance: understand the function.**

Judge icons in their real layout and at their real display size. Clarity, family consistency, and stable brand recognition outrank isolated cleverness or technical detail.

## Resolve direction in this order

1. Explicit current request.
2. Supplied reference image.
3. Approved icons from the same set.
4. Product-line profile.
5. Brand defaults in this skill.

Never silently change the requested icon count, exact captions, or approved artwork. A reference controls visual grammar—stroke, fill, corner, silhouette, negative space, enclosure behavior, complexity, and optical weight—not the new icon's subject.

## Interpret before drawing

For each copy block, identify:

- the customer-facing meaning;
- the object or action that must read without a caption;
- any state, change, or negation;
- the one cue that best separates it from a neighboring meaning.

Use one concept per icon. Do not turn supporting copy into extra objects or a miniature scene.

## Lock the family

Before mapping individual icons, lock:

- polarity and palette;
- line-and-fill construction;
- stroke weight, caps, joins, and corners;
- near-square optical footprint and baseline;
- negative-space width and detail budget;
- perspective logic;
- icon/caption spacing and typography when captions are present.

Read [references/style-guide.md](references/style-guide.md) for the construction, color, layout-profile, revision, and acceptance rules. Keep every approved dimension locked during revisions.

## Construct each icon

Default formula:

**1 dominant subject + 0–1 integrated supporting cue**

A second cue is allowed only when the meaning cannot be distinguished without it and both cues survive the small-size gate.

Prefer one continuous or visually interlocked silhouette. Merge state, action, connection, heat, flow, or removal cues into the main geometry. Avoid a collage of detached phone, arrow, Wi-Fi, badge, gear, and vehicle symbols.

Create design intent through silhouette, negative space, line-to-fill rhythm, and controlled asymmetry. “Simple” must not become generic: preserve one recognizable outer contour or meaningful cutout.

## Use the brand language

Stable defaults:

- modern, clean, direct, robust, flat, and symbolic;
- medium-to-bold line plus limited solid mass;
- consistent visual weight rather than a rigid fill ratio;
- black, charcoal, gray, and white as structural colors;
- industrial orange as a restrained functional accent;
- no decorative outer enclosure by default.

Orange marks the active state, heat/regeneration, key signal, critical flow, primary action, or important connection point. It must remain subordinate to the structural mass unless the current brief explicitly requests a monochrome orange set.

## Simplify structurally

When feedback says `太复杂`, `线条太多`, `简单一点`, or `不够直观`:

1. Keep the customer-facing meaning.
2. Remove or merge supporting cues.
3. Simplify interior structure.
4. Strengthen the dominant silhouette or one meaningful cutout.
5. Rebalance the entire family.

Do not merely thin strokes, delete arbitrary lines, or replace the icon with a generic symbol. Professional does not mean complicated.

## Adapt without breaking the family

Use one brand skeleton across placements and product lines; vary only the necessary detail budget.

- **Banner:** strongest silhouette, highest contrast, fewest interior details.
- **Amazon A+ / compact feature card:** immediate recognition, bold thumbnail reading, low detail.
- **Parameter module:** compact object plus value/unit cue only when the parameter cannot otherwise be distinguished.
- **System-diagnostic grid:** allow limited mechanical specificity so systems remain distinct; never become mini illustrations.
- **Battery / consumer-facing tools:** simpler, more universal metaphors.
- **Heavy-duty diagnostics:** slightly harder geometry and mechanical specificity, while preserving the shared construction.

Project-specific polarity, pure-outline treatment, background, or layout is an override—not automatically a permanent brand rule.

## Revise without drift

Classify feedback by dimension: metaphor, complexity, weight, line/fill balance, reference match, color, footprint, or layout.

Change only the named failing dimension. Preserve passing icons and the approved family lock. When only selected icons fail, rebuild only those icons, then recheck the whole set for weight, baseline, spacing, and color balance.

If the user asks for a genuinely new direction, change the dominant silhouette or composition logic. Small badge, spacing, or line tweaks do not constitute a new direction.

## Generate and inspect

When the user asks to generate icons, create the visual output; do not stop at a prose prompt.

The generation brief must state, in order:

1. exact icon count and layout;
2. shared style lock;
3. one sentence per icon describing meaning, dominant subject, and optional cue;
4. exact captions, if requested;
5. equal optical boxes, baselines, and separation;
6. exclusions for extra objects, unintended text, decorative frames, gradients, shadows, textures, mockups, and scene backgrounds.

Inspect the rendered result itself. Regenerate when any hard acceptance gate fails.

## Acceptance gates

Reject or revise an icon set when any of these fail:

- Each icon reads at both 24 px and 32 px.
- The icon remains understandable without its label.
- Distinctive silhouette survives monochrome use.
- No hairline gaps, fragile strokes, or detached micro-parts disappear at thumbnail size.
- Footprints are optically near-square and comparable without stretching unlike subjects.
- No icon is dramatically heavier, smaller, busier, or more detailed than its neighbors.
- Orange remains a controlled accent across the family.
- The result matches the supplied reference grammar.
- Exactly the requested number of icons and captions is present.

## Evidence threshold for evolving the skill

Classify new feedback before changing permanent guidance:

- **Cross-project pattern:** repeated across different projects → promote to the stable core.
- **Product-line pattern:** repeated within one family → keep as a product-line profile.
- **Layout behavior:** caused by display size or placement → keep as a layout rule.
- **One-off preference:** single instance or conflicting evidence → retain only for that project.

Repeated user rejection outweighs generic design convention. When evidence changes, strengthen, weaken, merge, or remove existing guidance instead of endlessly appending rules.

## Maintain this skill

When explicitly asked to update the skill:

1. Read the repository version of `SKILL.md` as the baseline.
2. Review real project evidence and classify it with the threshold above.
3. Add or update cases in [evals/cases.md](evals/cases.md) before changing guidance.
4. Make the smallest rule changes that resolve demonstrated failures.
5. Re-run every evaluation case and validate the skill folder.
6. Review the diff for one-off preferences, contradictions, and duplicated rules.
7. Commit the verified update; use Git history instead of a changelog.
