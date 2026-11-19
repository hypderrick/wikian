# Wikian

Wikian 是用于桌面版 Obsidian 的知识库整理插件。本仓库提供学员安装包、校验值和使用说明。已接入的知识库会在你确认后才开始整理。

## 下载 0.3.4

- [下载学员安装包](./knowledge-growth-sync-0.3.4-student.zip)
- [SHA-256 校验文件](./SHA256SUMS.txt)

## 安装和升级

1. 关闭桌面版 Obsidian。首次安装时，解压 ZIP，把整个 `knowledge-growth-sync` 文件夹放到知识库的 `.obsidian/plugins/` 目录。
2. 已安装旧版时，把新版文件复制到现有的 `knowledge-growth-sync` 文件夹并覆盖同名文件。保留原目录、`data.json` 和聊天记录。
3. 重新打开 Obsidian，在「设置 → 第三方插件」启用 Wikian。首次使用时，按提示创建标准目录，从侧栏打开「库体检」，验证后确认接入。
4. 整理需要本机有可用的 Codex CLI 或 Claude Code。待整理任务会出现在「整理」页，点击「开始整理」后才调用模型。

## 版权与使用

© 2026 何耀澎。Wikian 自有部分保留所有权利。

允许学员下载、安装和使用本仓库提供的 Wikian 安装包。未经权利人许可，请勿将 Wikian 自有部分二次分发、转售或作为独立产品发布。随包分发的第三方组件适用各自的许可证。
