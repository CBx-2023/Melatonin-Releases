# Melatonin

面向律所的桌面 Agent 工作区。**项目即案件，项目下按对话开展工作。**

本仓库只发布使用说明、版本记录和桌面安装包，不包含应用、后台或网站的源代码。GitHub 自动提供的 “Source code” 压缩包仅包含本仓库的说明文件，不是应用源码或安装包。

- [官网](https://melatonin.claimclaw.org/)
- [发行版本与下载](https://github.com/CBx-2023/Melatonin-Releases/releases)
- [使用指南](docs/user-guide.md)
- [开发与平台状态](docs/status.md)
- [问题反馈](https://github.com/CBx-2023/Melatonin-Releases/issues)
- [第三方版权声明](THIRD_PARTY_NOTICES.md)

## 下载安装

当前测试预发行版：[v0.1.0-beta.34](https://github.com/CBx-2023/Melatonin-Releases/releases/tag/v0.1.0-beta.34)，支持 **macOS Apple Silicon**。

- [下载 DMG](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.34/melatonin-0.1.0-beta.34-arm64.dmg)
- [下载 ZIP](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.34/melatonin-0.1.0-beta.34-arm64.zip)
- [SHA-256 校验值](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.34/SHA256SUMS.txt)

**本版为 ad-hoc 签名、未 Apple 公证的测试包。** macOS 可能阻止首次启动，请先阅读 Release 中的签名说明。本次没有 Windows/Intel Mac/Linux 安装附件。不要下载 “Source code” 作为安装包。

macOS、Windows 和 Linux 的功能验证状态分别记录在[平台状态](docs/status.md)。本仓库不提供源码构建步骤，也不承诺尚未发行版本的签名或兼容性。

## 开始办案

1. 从发行版本下载适用的桌面软件。
2. 获取律所管理员提供的账号或邀请码，在「设置 → 通用 → 律所账号」登录或激活。
3. 添加项目文件夹，作为案件目录；项目下创建对话。
4. 打开顶栏「案件材料与成果」，填写案件信息、导入材料，并在对话中安排分析或起草。
5. 点击引用核对原文，修正事实、复核文书，按需导出 DOCX/PDF。

模型由管理后台统一配置；语言、主题、外观、通知及其他桌面设置保持原有使用方式。

## 反馈时保护案件信息

公开 Issue 中请只提供去除敏感信息的复现步骤、软件版本和系统版本，不上传客户卷宗、账号密码、邀请码、模型密钥或包含这些信息的日志。
