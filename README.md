# Wikian


Wikian 是一款桌面版 Obsidian 插件。它连接本机的 Codex CLI 或 Claude Code，让你在 Obsidian 里查询笔记、基于库内资料创作，并按需整理知识库。


## 功能


- **查询&创作**：在侧栏提问或创作。首次启用后即可查询、创作和切换聊天权限，无需登录 Wikian。回答的引用默认折叠在「知识库依据」。输入 `@` 可以引用库内笔记。
- **整理**：查看待整理资料，确认后再开始分批处理。
- **定稿和维护**：在侧栏处理定稿并维护知识库。


## 下载 0.3.6


- [GitHub Release v0.3.6](https://github.com/hypderrick/wikian/releases/tag/v0.3.6)
- [下载安装包](https://github.com/hypderrick/wikian/releases/download/v0.3.6/Wikian-0.3.6.zip)
- [SHA-256 校验文件](https://github.com/hypderrick/wikian/releases/download/v0.3.6/SHA256SUMS.txt)


## 安装


查询、创作和整理需要桌面版 Obsidian，以及本机已配置且可用的 Codex CLI 或 Claude Code（任选其一）。


1. **首次安装**：关闭 Obsidian，解压 ZIP，把整个 `wikian` 文件夹放到知识库的 `.obsidian/plugins/` 目录。
2. 重新打开 Obsidian，在「设置 → 第三方插件」启用 Wikian。首次启用时按提示创建标准目录，打开 Wikian 侧栏即可查询。
3. 要使用整理、定稿和维护，先从侧栏打开「库体检」并完成接入。待整理任务会出现在「整理」页，点击「开始整理」后才调用模型处理。


## 升级

关闭 Obsidian 后，用新版安装包覆盖 `wikian` 目录内的 `main.js`、`manifest.json` 和 `styles.css`，保留原有设置与历史对话。

## 版权与使用


© 2026 何耀澎。Wikian 自有部分保留所有权利。


允许下载、安装和使用本仓库提供的 Wikian 安装包。未经权利人许可，请勿将 Wikian 自有部分二次分发、转售或作为独立产品发布。随包分发的第三方组件适用各自的许可证。


