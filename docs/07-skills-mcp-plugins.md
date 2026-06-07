# Skills、MCP 与插件

如果你只会一次次写提示词，Codex 的价值会停留在“临时帮忙”。如果你把重复流程沉淀成 Skills、MCP 和插件，它才会变成工作系统。

## AGENTS.md、Skills、MCP 的区别

| 能力 | 解决什么 |
| --- | --- |
| AGENTS.md | 让 Codex 知道这个项目的规则 |
| Skills | 把重复任务变成可复用流程 |
| MCP | 连接外部工具、数据和系统 |
| 插件 | 把浏览器、GitHub、Linear、Figma 等能力接进来 |

## 什么适合做成 Skill

- 每周固定更新的教程。
- 小红书封面审查。
- GitHub 趋势雷达。
- 发布包检查。
- 前端移动端验收。

## Skill 模板

```markdown
# Skill Name

Use when ...

## Inputs

- Source files
- Target output
- Safety boundary

## Workflow

1. Read context.
2. Produce draft.
3. Run checks.
4. Return evidence.

## Stop Conditions

- Missing credential.
- Unclear public/private boundary.
- User approval required.
```

## 我的建议

先不要追求“全自动”。先把一个流程写清楚，再让 Codex 稳定重复。能稳定重复，才有资格自动化。
