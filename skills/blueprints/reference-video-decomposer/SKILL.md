---
name: reference-video-decomposer
description: Decompose reference videos into reusable editing templates. Use when the user asks to analyze finished videos, extract keyframes, detect rhythm, summarize subtitle and visual structure, compare references, or turn examples into executable editing templates.
---

# Reference Video Decomposer

## Purpose

Transform finished reference videos into reusable editing guidance: structure, rhythm, shot sequence, subtitle style, audio use, and executable templates.

This skill is project-agnostic. Do not bind the output to one brand unless the user explicitly asks.

## Inputs

Possible inputs:

- A folder of reference videos
- One reference video path
- Project description
- Target video type
- Desired platform and duration

## Workflow

1. Inspect reference files.
   - List duration, resolution, codec, frame rate, and file size.
   - Separate short-form templates from long narrative examples.

2. Generate visual evidence.
   - Extract keyframes or contact sheets.
   - Review keyframes before writing conclusions.
   - Compare multiple references when available.

3. Classify reference types.
   - Product fast cut
   - Store story
   - Timeline/process
   - Takeaway/delivery
   - Talking-head explainer
   - Tutorial
   - Review

4. Decompose each useful reference.
   - Opening hook
   - Middle proof/process
   - Product/result shots
   - Trust/social proof
   - Ending or loop
   - Subtitle style
   - Rhythm and cut density

5. Produce an executable template.
   - Segment formula
   - Required material categories
   - Target duration
   - Output format
   - Human confirmation points

6. Save outputs.
   - Report
   - Contact sheet or keyframe summary
   - Recommended MVP template

## Report Structure

```markdown
# Reference Video Decomposition Report

## Purpose
## Reference Overview
## Per-Video Decomposition
## Reusable Templates
## Recommended MVP Template
## Subtitle and Text Style
## Audio and Rhythm Notes
## Execution Guidance
## Open Confirmations
```

## Template Heuristics

Product or food fast cut:

```text
result hook
→ appetite/action close-up
→ process/proof
→ serving or usage
→ result close
```

Store or brand story:

```text
people/store hook
→ credibility proof
→ process and effort
→ customer/order evidence
→ trust or emotional ending
```

Timeline or process:

```text
core claim
→ time marker
→ preparation
→ main work
→ peak output
→ ending or series hook
```

Delivery or takeaway:

```text
production action
→ finished items
→ packing or handoff
→ store/customer/runner
→ quick result close
```

## Safety Rules

- Do not copy copyrighted reference material into final deliverables.
- Do not invent prices, addresses, or factual claims.
- Flag absolute claims, health claims, unconfirmed location, and unconfirmed price.
- Keep the first MVP template simple enough to execute with available material.
- Use approximate timestamps unless precise scene logs are available.

## Outputs

- Reference overview
- Keyframe/contact sheet summary
- Template recommendation
- Shot formula
- Subtitle style guide
- Editing rhythm notes
- Human confirmation list
