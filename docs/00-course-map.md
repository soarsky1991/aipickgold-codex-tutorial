# Codex 完整课程地图

我是智辰老师。这个课程地图把 Codex 学习拆成 12 部分、60 个小节。你可以把它当成学习导航，也可以把它当成建站、写教程、做视频和做开源仓库的内容大纲。

## 1. 基础入门

1. Codex 是什么：软件开发 coding agent，不是普通聊天机器人。
2. 四种入口：App、CLI、IDE、Web / Cloud。
3. 工具对比：Codex、Claude Code、Cursor、Copilot 的边界。
4. 适合与不适合：读代码、做功能、修 Bug、写测试；不要无审查碰生产。
5. 账号与认证：ChatGPT 登录、API key、组织权限。
6. 第一条任务：只读扫描、总结结构、提出小任务。
7. 模型与本地环境：如何判断哪些配置可以公开，哪些只能内部使用。

## 2. 桌面端入门

1. Codex App 是什么：多项目、多线程、本地和云端任务入口。
2. 下载、安装和登录：先用小项目练习。
3. App 界面总览：线程、diff、终端、设置、浏览器。
4. Local / Worktree / Cloud：三种模式怎么选。
5. 多项目与多线程：并行任务如何避免互相污染。
6. App 设置：通知、权限、外观、Git。
7. 快捷键与命令菜单：让日常操作变快。
8. App Slash Commands：用命令控制上下文和任务。

## 3. 工程工作流

1. Git diff、分支和 PR 描述。
2. Worktree 隔离开发流程。
3. 内置浏览器与本地 Web 预览。
4. Chrome 插件：用现有登录态验收页面。
5. Computer Use：什么时候用桌面操作，什么时候不要用。

## 4. CLI 与终端

1. 安装 Codex CLI。
2. CLI 基础命令。
3. 常用全局参数。
4. CLI Slash Commands。
5. 会话管理：resume 与 fork。
6. 非交互模式：`codex exec`。

## 5. IDE 与 Cloud

1. Codex IDE 扩展。
2. IDE 工作流：小步编辑与即时验证。
3. Codex Web 与 Cloud 入门。
4. 云端任务：什么任务适合 Cloud。
5. GitHub 集成：从 Issue 到 PR。

## 6. 核心概念

1. Agent Loop：Codex 的执行循环。
2. Thread、Turn 与 Context。
3. Sandbox 与 Approval：两条边界。
4. 模型与推理强度。

## 7. 配置与定制

1. `config.toml`：用户级与项目级配置。
2. Permissions Profile。
3. Rules：命令级允许、提示、拒绝。
4. Hooks：生命周期里的确定性脚本。

## 8. 扩展能力

1. AGENTS.md。
2. Skills。
3. MCP。
4. 插件中文速查表。
5. 浏览、安装、启用、卸载插件。

## 9. 实战工作流

1. 理解陌生代码库。
2. 实现新功能。
3. 修 Bug。
4. 写测试。
5. 代码审查。
6. 重构与迁移。
7. 前端 UI 开发。

## 10. 集成与自动化

1. Slack / Linear 等集成。
2. CI/CD 与 GitHub Action。
3. Codex SDK 与 App Server。

## 11. 安全与治理

1. 个人使用安全清单。
2. 企业治理与上线路径。

## 12. 速查与附录

1. CLI 命令速查。
2. Slash 命令速查。
3. FAQ。
4. 术语表。

## 我的学习建议

先不要贪多。你只要用一个小项目完成“只读扫描 -> 写 AGENTS.md -> 小改动 -> 跑测试 -> 总结 diff”这条链路，就已经超过大多数只收藏教程的人。
