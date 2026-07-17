# D:\AiWorkArea\code

AI 编程工作区，用于存放 AI Agent（Codex / Claude Code 等）协作开发的代码项目。

## 仓库职责

- 维护可直接运行或复用的代码、页面与脚本
- 统一保存项目文档、Agent 会话归档和提示词模板
- 通过状态记录与技术决策文档保留项目上下文
- 排除环境变量、凭据、令牌、Cookie、私钥等敏感信息

## 目录结构

```
code/
├── README.md              ← 你在这里
├── AGENTS.md              ← AI Agent 行为规范
├── PROJECT_STATUS.md      ← 项目状态记录
├── DECISIONS.md           ← 架构/技术决策记录
├── .gitignore             ← Git 忽略规则
├── sessions/              ← Agent 会话输出归档
├── docs/                  ← 项目文档
└── prompts/               ← 提示词模板库
```

各类内容的准入与命名规则见对应目录中的 `README.md`。

## 维护入口

- 开始工作前阅读 `AGENTS.md` 并检查 `.gitignore`
- 功能或阶段发生变化时更新 `PROJECT_STATUS.md`
- 形成重要且长期有效的技术选择时更新 `DECISIONS.md`
- 每次 Agent 协作结束后在 `sessions/` 中留下归档

## 快速开始

```bash
git clone <this-repo-url>
cd code
```
