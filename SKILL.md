---
name: visual-feedback
description: >
  Use when the Art Director needs to give specific directional feedback on visual
  or motion deliverables from Visual Designer or Motion Designer. Triggered when
  a designer @mentions the Art Director with work ready for review.
  Do NOT use for copy feedback — use feedback-comment instead.
---

# Visual feedback

## Purpose
Visual feedback from the Art Director must be specific enough that the designer can act immediately. Vague feedback ("make it more dynamic") costs heartbeats. Precise feedback ("increase the visual weight of the headline by 40%, shift from centered to left-aligned") gets results.

## Evaluation framework

For each deliverable, evaluate in order:

### 1. Concept alignment
- Does the visual execution match the art direction document?
- Does it communicate the single visual concept?
- Does it feel like the same campaign as other assets?

### 2. Craft
- Typography: hierarchy, spacing, weight, alignment
- Color: palette adherence, contrast, balance
- Composition: visual weight, breathing room, focal point
- Technical: file specs, resolution, safe zones respected

### 3. Platform fit (for social assets)
- Does it stop the scroll?
- Does it work without sound (for video)?
- Does it hold up at small sizes?

## Output format

```
## Visual feedback — [Asset name]

**Overall**: [APPROVED / REVISION NEEDED / MAJOR REWORK]

---

**What's working**
[Specific — name the exact element and why it works]

**Issue 1 — [Category: Typography / Color / Composition / Concept / Technical]**
Problem: [precise description]
Fix: [exact instruction — measurements, values, directions where possible]
Example: "Reduce headline size from ~80px to ~56px. Increase body copy leading to 1.4. Left-align both."

**Issue 2** (if needed)
[same structure]

**Next step**
[Exactly what to revise. Be literal. "Revise headline treatment only — keep everything else."]
```

## Rules
- Maximum 3 revision items per review. If you have more, the art direction was unclear — rewrite it first.
- Every issue must have a fix. "This doesn't work" without a solution is not feedback.
- If approving: mark the asset explicitly approved and @mention Creative Director.
- If major rework needed: @mention Creative Director before sending feedback — don't loop indefinitely without CD visibility.
