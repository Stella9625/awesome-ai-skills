# Product Ideas Lab

## Project Overview
这是坑坑的产品创意实验室。收集、评估和打磨产品 idea，借助 GStack 工具形成有商业价值的方案。

## Workflow
1. **收集** - 把灵感记录到 `ideas/` 目录，每个 idea 一个 markdown 文件
2. **评估** - 使用 `/plan-ceo-review` 从 CEO 视角审视商业价值
3. **设计** - 使用 `/plan-eng-review` 评估技术可行性
4. **打磨** - 使用 `/office-hours` 模拟投资人问答，找到薄弱环节
5. **归档** - 通过评估的 idea 移入 `validated/`，不可行的移入 `archived/`

## Directory Structure
```
ideas/          # 原始创意（待评估）
validated/      # 通过评估的方案
archived/       # 已归档的创意
templates/      # idea 模板
reviews/        # GStack 评审记录
```

## Idea File Format
每个 idea 文件遵循 `templates/idea-template.md` 的格式。

## GStack Commands Cheat Sheet
- `/plan-ceo-review` - CEO 视角评估：市场规模、商业模式、竞争优势
- `/plan-eng-review` - 工程视角评估：技术架构、开发成本、可行性
- `/plan-design-review` - 设计视角评估：用户体验、交互流程
- `/office-hours` - 模拟投资人/导师问答，压力测试你的 idea
- `/design-consultation` - 产品设计咨询
- `/retro` - 复盘已执行的项目

## Conventions
- idea 文件名格式: `YYYY-MM-DD-简短描述.md`
- 评审记录格式: `reviews/YYYY-MM-DD-idea名称-review类型.md`
- 状态标签: `draft` → `reviewing` → `validated` / `archived`
