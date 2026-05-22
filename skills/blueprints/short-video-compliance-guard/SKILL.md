---
name: short-video-compliance-guard
description: Provide compliance guardrails for short-form video planning, production, review, publishing, and archiving. Use for subtitle, caption, music, privacy, customer image, price, claims, advertising wording, AI pre-review, human final-review checklist, and release gating.
---

# Short Video Compliance Guard

## Purpose

Keep compliance upstream in short-video production.

Do not treat compliance as only a final review step.

When this skill is active, the workflow must:

1. Read project rules before selecting topic, material, subtitle, or music.
2. Avoid high-risk content during task planning.
3. Produce AI pre-review after draft generation.
4. Prepare human final-review checklist before release.

## When To Use

Use when the user asks to:

- Review whether a short video is compliant.
- Create or update video compliance rules.
- Generate a short-video edit plan where compliance matters.
- Audit subtitles, captions, music, privacy, customer images, prices, claims, or advertising wording.
- Create AI review reports, human review checklists, release gates, or publishing records.

## Pre-Production Guard

Before topic selection, material selection, subtitles, or music:

- Read project description.
- Read project compliance constraints.
- Identify hard boundaries: price, address, activity, claims, privacy, music rights, customer faces, order/payment information.
- Pause and ask for confirmation when risky facts or claims are requested.

Default safe boundaries:

- Do not add prices, addresses, opening hours, discounts, or events unless confirmed.
- Do not use absolute claims such as best, number one, lowest price, must eat, or equivalent wording.
- Do not imply health, treatment, weight loss, or body-regulation effects.
- Do not feature customer faces, children, phone numbers, order numbers, payment codes, or full receipts.
- Mark music as pending publish-right confirmation unless the project says otherwise.

## Risk-Aware Content Planning

Every edit plan should include:

- Compliance rules read: yes/no
- Price/address/activity used: yes/no/pending confirmation
- Customer or crowd footage used: yes/no/pending confirmation
- Order/receipt/payment information present: yes/no/pending confirmation
- Music status: pending / publishable / replace
- Risk-word check: passed / needs edit
- Human confirmation required: list concrete points

Prefer low-risk content:

- Product close-ups
- Production actions
- Serving/result shots
- Environment without identifiable faces
- Packaging without private order details
- Factual subtitles

Require confirmation:

- Customer dining
- Crowded store shots
- Receipts, menus, orders, payment screens
- Promotion or discount videos
- Health, authority, exclusive, sold out, queue, or similar claims

## AI Compliance Pre-Review

After draft generation:

1. Review subtitles and on-screen text.
2. Review keyframes or described video content.
3. Review music/source/authorization status.
4. Review whether content violated pre-production constraints.
5. Classify risks as high, medium, low, or none.
6. Output a structured AI pre-review report.

## Human Final Review Gate

AI review never replaces human final review.

Human review must confirm:

- Full video playback
- Customer face and privacy risks
- Order, phone, payment, receipt, QR code, or menu risks
- Subtitle accuracy
- Brand wording
- Music publish rights
- Final publish decision

If high-risk issues remain, do not mark the video publishable.

## Output Format

AI pre-review report:

```text
Conclusion: pass / modify / uncertain
Risk level: high / medium / low / none

Issues:
1. Location:
   Type:
   Reason:
   Fix:

Human review priorities:
1. ...
```

Human checklist:

```text
Final decision: pass / modify / uncertain
Human explanation:
```

## Common Fixes

- Replace extreme claims with factual sensory wording.
- Replace customer shots with product, serving, or environment shots.
- Crop, blur, or replace private order/payment footage.
- Remove prices or activity claims until confirmed.
- Replace uncertain music with a confirmed publishable track.

## Limitation

This skill is a workflow guardrail, not legal advice and not a real-time official platform policy feed.

If the user needs current official policy, verify with official platform sources before final conclusions.
