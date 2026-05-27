# Changelog

## 2026-05-27

### Changed

- Replaced the material naming pattern with the concise Chinese format `品牌名_日期_景别-画面内容`, appending a sequence only when names collide.
- Converted the public `material-flow-organizer` skill blueprint into a Chinese template and added `templates/素材命名与归档标准模板.md`.
- Updated the material Agent prompt and MVP workflow so naming previews follow the new standard before any confirmed file operation.

## 2026-05-26 (v3)

### Changed

- Reframed `README.md` as the controller Agent's primary entrypoint instead of a user-oriented introduction page.
- Added controller startup reading order, customer communication duties, stage gates, and minimum system configuration to the repository homepage.
- Repositioned `docs/快速开始.md` as customer-facing material the controller may send after taking ownership of setup.

## 2026-05-26 (v2)

### Changed

- Reduced the default operating model to controller, material, and content-production Agents; removed the review/publishing Agent role.
- Assigned reference-material analysis and writing/clip standards to the content-production Agent; limited the material Agent to asset organization.
- Redesigned Feishu templates around `视频任务总表`, `素材库表`, and `Agent 执行记录表`, with human final review and publishing decisions recorded by the controller.

## 2026-05-26

### Changed

- Revised onboarding so the controller builds Feishu collaboration tables and specialist Agents before running the first complete MVP.
- Added `docs/首次协作说明.md` for the controller's first user-facing workflow explanation.
- Added Feishu CLI installation, non-blocking authorization, and Windows PowerShell JSON/BOM troubleshooting guidance.

## 2026-05-23

### Added

- Initial generic project package.
- Main project guide document.
- Controller Agent guide.
- MVP workflow template.
- Feishu Base setup guide.
- Collaboration table CSV templates.
- Agent prompt templates.
- Compliance checklist and review rules.
- Skill blueprints:
  - `material-flow-organizer`
  - `reference-video-decomposer`
  - `short-video-compliance-guard`
- Public release and privacy check.
- Quick start guide.
- Installation and usage guide.
- Roadmap.
- Fully fictional bakery example project.
- README clarification that the default operating environment is Feishu Base + Codex.
