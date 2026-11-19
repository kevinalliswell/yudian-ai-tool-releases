# yudian-ai-tool-releases

yudian-ai-tool 宇电仪表 AI 工具 的**公开发布通道**：只存放 Release 安装包、更新签名（`.sig`）和应用内更新清单 `latest.json`。

- 源码在私有仓库 `yudian-ai-tool`，本仓库不含任何源码，也不接收 issue / PR。
- 应用内更新地址：`https://github.com/kevinalliswell/yudian-ai-tool-releases/releases/latest/download/latest.json`
- Release 由源码仓库的发布工作流自动创建为草稿，维护者复核后才公开。
- 更新包均经 Tauri updater 私钥签名，客户端会用内置公钥校验，篡改的包会被拒绝安装。
