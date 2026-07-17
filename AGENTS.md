# AGENTS.md — AI Agent 行为规范

## 安全规则（必须遵守）

1. **禁止读取敏感文件**：不得读取 `.env`、`*.secret`、`*token*`、`*cookie*`、`credentials*`、`*.pem`、`*.key` 等文件
2. **每次操作前检查 `.gitignore`**：确保不会意外提交敏感信息
3. **写入文件前确认路径在仓库内**：不修改仓库外的系统文件

## 工作约定

- 所有 Agent 会话输出归档到 `sessions/YYYY-MM-DD-<描述>.md`
- 新增项目文档放入 `docs/`
- 可复用的提示词模板放入 `prompts/`
- 重要技术决策记录到 `DECISIONS.md`
- 项目状态变更更新到 `PROJECT_STATUS.md`

## 提交规范

- 提交信息使用中文
- 格式：`<类型>: <描述>`（如 `feat: 添加用户登录`、`fix: 修复空指针`）
