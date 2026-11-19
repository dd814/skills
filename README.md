# Skills

这里收录可以独立安装的技能。每个技能目录的 `SKILL.md` 说明适用场景、用法和依赖。

| 技能 | 用途 |
|---|---|
| [Structure Atlas · 复杂结构图谱](structure-atlas/SKILL.md) | 用关系总图、具体流程和可展开的细节解释复杂结构。在同一份离线 HTML 中记录项目进展，并复制讨论上下文。 |
| [WorkBuddy 微信桥接](codex-workbuddy-wechat-bridge/SKILL.md) | 将 WorkBuddy 的微信助理连接到本机已有的 Codex 聊天。包含桥接程序、配置说明和测试。 |

## 安装

下载仓库或所需版本的源码，将所选技能的**完整目录**放入 Codex 的 `skills` 目录（默认 `~/.codex/skills/`）。安装后的结构例如 `~/.codex/skills/structure-atlas/SKILL.md`。同时保留技能目录中的模板、脚本和参考文件。

- **Structure Atlas** 使用 Python 3 生成单文件 HTML。渲染方法和输入示例见[模板说明](structure-atlas/references/html-template.md)。
- **WorkBuddy 微信桥接** 需要 Python 3.10+ 和支持自定义 MCP 的 WorkBuddy，按[桥接技能说明](codex-workbuddy-wechat-bridge/SKILL.md)配置。

## Structure Atlas 版本

可从[仓库版本标签](https://github.com/dd814/skills/tags)选择对应快照。标签以技能名开头，方便按技能查找。

| 版本 | 内容 |
|---|---|
| `structure-atlas-v1.1.0` | 新增项目进展视图、模块旁的最新标注、历史记录和讨论上下文复制。旧图谱的输入格式仍可用。 |
| `structure-atlas-v1.0.0` | 首版，提供关系总图、阅读路径、分层细节和离线 HTML。可查看[首版提交](https://github.com/dd814/skills/commit/fde787f9f9e302bab32f2274f79f436028351fcb)。 |
