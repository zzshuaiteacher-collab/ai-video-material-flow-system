# Skills 目录

本目录用于存放可迁移的 skill 蓝图。

注意：这里放的是通用脱敏版，不是某台电脑上的个人 skill 原件。

## 已包含蓝图

| Skill | 说明 |
| --- | --- |
| `blueprints/material-flow-organizer` | 素材扫描、命名、分类、首次整理、增量整理 |
| `blueprints/reference-video-decomposer` | 参考视频拆解、关键帧、节奏、模板提炼 |
| `blueprints/short-video-compliance-guard` | 内容生产前置合规、AI 初审、人工终审护栏 |

## 使用方式

用户可以根据自己的 Agent 平台，把 `blueprints/<skill-name>/SKILL.md` 安装到对应的 skill 目录。

如果当前平台不支持 skill，也可以把对应 `SKILL.md` 当作专项工作流文档，让总控 Agent 或专项 Agent 读取。

## 后续建议沉淀

1. 内容生产任务单 skill
2. 视频生成验收 skill
3. 发布归档与数据回填 skill
4. 数据复盘 skill

## 创建或更新规则

创建 skill 前必须遵守：

```text
先评估
→ 后确认
→ 再创建
```

如果用户只是问“这个能不能写成 skill”，总控 Agent 应先判断并解释，不要直接创建。
