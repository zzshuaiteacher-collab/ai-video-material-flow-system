---
name: material-flow-organizer
description: Organize reusable media material flows for video projects. Use when the user asks to scan material folders, standardize names, classify newly added media, create a material ledger, detect duplicates, or maintain first-time and incremental material organization workflows.
---

# Material Flow Organizer

## Purpose

Turn loose media files into a reusable material library: scanned, named, classified, reviewable, and ready for editing.

This skill is project-agnostic. Do not hard-code one brand, one folder, or one local machine path.

## Required Rule

Always use a two-step workflow:

```text
preview plan
→ user confirmation
→ execute rename or move
```

Do not move, rename, delete, overwrite, or deduplicate original files during preview.

## Modes

### First-Time Organization

Use when:

- Materials are in one loose folder.
- No stable folder taxonomy exists.
- The user wants a naming and classification standard.

Steps:

1. Scan media files.
2. Capture path, extension, size, duration, resolution, and existing folder.
3. Infer project naming rules from documents or user instructions.
4. Propose folder taxonomy.
5. Propose standardized names.
6. Generate a reviewable ledger.
7. Wait for user confirmation.
8. Execute only confirmed moves and renames.

### Incremental Organization

Use when:

- Existing category folders already exist.
- The user added new files.
- The task is to process only newly added files.

Steps:

1. Read existing folder structure.
2. Identify new or unorganized files.
3. Apply existing naming rules.
4. Continue numbering without collisions.
5. Generate incremental preview.
6. Execute after confirmation.
7. Update ledger and manifest.

## Suggested Categories

Adapt to the project, but start from:

- product close-up
- production/process
- serving/result
- environment
- people/customer
- takeaway/packaging
- price/menu
- talking head
- music
- reference
- output
- archive
- `99_待分类`

## Naming Pattern

Recommended generic pattern:

```text
项目或品牌_日期_素材类型_主体_镜头动作_序号_规格.扩展名
```

Example:

```text
ProjectA_20260521_raw_product_closeup_001_1080x1920.mp4
```

## Confidence Rules

| Confidence | Meaning | Action |
| --- | --- | --- |
| High | File clearly matches category and subject | Propose category directly |
| Medium | Likely match but subject/action may be ambiguous | Mark as pending confirmation |
| Low | Content is unclear or metadata is insufficient | Put into `99_待分类` |

## Safety Rules

- Never overwrite files.
- Never delete duplicates automatically.
- Never treat reference videos as publishable material unless the user says so.
- Never assume music is licensed.
- Keep original files untouched until explicit confirmation.
- Before moving files, verify paths stay within the intended project folder.
- Record every move or rename in a manifest.

## Outputs

Preview output:

- Material ledger
- Classification plan
- Naming standard summary
- Pending confirmations

Execution output:

- Updated folder structure
- Move/rename manifest
- Updated material ledger
- Files organized, skipped, and pending
