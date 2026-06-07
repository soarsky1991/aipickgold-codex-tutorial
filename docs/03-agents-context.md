# 写一份让 Codex 真正懂项目的 AGENTS.md

AGENTS.md 是项目给 Codex 的工作说明书。它把命令、边界、风格和验收标准写成可复用上下文。

## 至少写什么

- 项目目标：这个仓库解决什么问题。
- 常用命令：安装、开发、构建、测试、预览。
- 编辑边界：哪些目录可以改，哪些文件不能碰。
- 验收标准：什么算完成，必须跑哪些检查。

## 公开内容边界

- 内部策略不公开。
- 来源许可不清楚的内容只做内部研究，不进入公开源码和页面。
- token、SSH、OSS、DNS、env 路径都不能提交。

## 模板

```markdown
# Project Rules

- Run `npm run build` before publishing.
- Do not edit deployment secrets or env files.
- Public copy must not reveal private research targets or collection targets.
- Verify mobile width around 390px before final handoff.
```
