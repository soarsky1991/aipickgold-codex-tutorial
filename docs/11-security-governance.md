# 安全与治理

个人使用 Codex，也要有治理意识。因为 AI 工具一旦能读文件、改代码、跑命令，就不再只是聊天工具。

## 个人安全清单

- 项目里不要放明文密钥。
- 公开截图前检查路径、token、邮箱、服务器信息。
- 让 Codex 改文件前先 `git status`。
- 高风险命令先解释再执行。
- 发布动作保持人工确认。

## 团队治理清单

- 哪些仓库能用 Codex。
- 哪些目录禁止修改。
- 哪些数据不能进入上下文。
- PR 需要哪些验证。
- 出错时谁负责回滚。

## AGENTS.md 中的安全段落

```markdown
## Safety

- Never print or commit secrets.
- Do not access production credentials.
- Ask before running destructive commands.
- Run tests before final handoff.
- Public docs must not reveal internal research targets.
```

## 我的判断

真正能长期使用 AI 的团队，不是最会写提示词的团队，而是最会设计边界、验证和复盘的团队。
