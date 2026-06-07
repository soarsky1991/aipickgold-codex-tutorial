# 03. 写一份让 Codex 真正懂项目的 AGENTS.md

`AGENTS.md` 是项目给 Codex 的工作说明书。你可以把它理解成“给 AI 合伙人的入职手册”。

我做项目时，最看重的不是 Codex 一次回答多聪明，而是它每次进项目都能按同一套规则行动。

## 至少写什么

- 项目目标：这个仓库解决什么问题。
- 常用命令：安装、开发、构建、测试、预览。
- 编辑边界：哪些目录可以改，哪些文件不能碰。
- 公开边界：哪些内容能公开，哪些只属于内部研究。
- 验收标准：什么算完成，必须跑哪些检查。
- 交付格式：最后要给 diff、测试结果、截图还是发布包。

## 我常用的最小模板

```markdown
# Project Rules

## Goal
- This project is the public AI PickGold Codex learning site.

## Commands
- Run `npm run build` before publishing.
- Use local preview before deployment.

## Boundaries
- Do not edit secrets, env files, deployment credentials, or private notes.
- Public copy must not reveal private notes, account details, credentials, or internal strategy.
- Use original AI PickGold wording for public docs.

## Verification
- Check mobile width around 390px.
- Confirm images and videos load.
- Summarize changed files and test results before final handoff.
```

## 为什么这件事重要

没有 `AGENTS.md`，Codex 会靠猜。  
有了 `AGENTS.md`，Codex 才能按你的项目规则行动。

这也是我做 AI 变现和个人 IP 内容时很看重的一点：每一次项目执行，都要留下下一次可以复用的规则。

## 公开内容边界

公开仓库、网站、README、SEO 和项目管理文档，只写可以对外展示的信息。非公开资料、私人策略、账号细节和密钥路径，都不要进入公开材料。

## 练习任务

```text
请根据当前项目生成一份 AGENTS.md 草稿。
要求包含：项目目标、常用命令、可编辑目录、禁止触碰内容、公开内容边界、验收标准。
先输出草稿给我 review，不要直接写文件。
```

下一步：[04. CLI 与终端自动化](04-cli-terminal.md)
