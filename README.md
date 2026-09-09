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

当前测试预发行版：[v0.1.0-beta.35](https://github.com/CBx-2023/Melatonin-Releases/releases/tag/v0.1.0-beta.35)，提供 **macOS Apple Silicon** 测试包与 **Windows x64** 未签名试点包。

- [macOS DMG](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.35/melatonin-0.1.0-beta.35-arm64.dmg)
- [macOS ZIP](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.35/melatonin-0.1.0-beta.35-arm64.zip)
- [macOS SHA-256 校验值](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.35/SHA256SUMS.txt)
- [Windows 安装程序（NSIS）](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.35/melatonin-0.1.0-beta.35-x64-setup.exe)
- [Windows 便携版](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.35/melatonin-0.1.0-beta.35-x64-portable.exe)
- [Windows SHA-256 校验值](https://github.com/CBx-2023/Melatonin-Releases/releases/download/v0.1.0-beta.35/SHA256SUMS-Windows.txt)

**macOS 包为 ad-hoc 签名，未完成 Apple 公证；Windows 包未签名，仅供试点。** 安装前请核对对应平台的 SHA-256 校验文件，并阅读 Release 中的签名与系统安全提示说明。Windows 已通过真实 Windows runner 上的源应用授权/案件测试及打包应用 OAuth 测试；用户机器安装与 Word/WPS 兼容性仍需试点验收。模型请求使用管理员配置的服务，额度与使用记录可在用户中心查看。本次没有 Intel Mac/Linux 安装附件。不要下载 “Source code” 作为安装包。

macOS、Windows 和 Linux 的功能验证状态分别记录在[平台状态](docs/status.md)。本仓库不提供源码构建步骤，也不承诺尚未发行版本的签名或兼容性。

## 开始办案

1. 从发行版本下载适用的桌面软件。
2. 在网站完成管理员的邮件邀请激活，再到「设置 → 通用 → 律所账号」选择「通过浏览器登录」并确认授权。
3. 添加项目文件夹，作为案件目录；项目下创建对话。
4. 打开顶栏「案件材料与成果」，填写案件信息、导入材料，并在对话中安排分析或起草。
5. 点击引用核对原文，修正事实、复核文书，按需导出 DOCX/PDF。

模型由管理后台统一配置；语言、主题、外观、通知及其他桌面设置保持原有使用方式。

## 反馈时保护案件信息

公开 Issue 中请只提供去除敏感信息的复现步骤、软件版本和系统版本，不上传客户卷宗、账号密码、邀请码、模型密钥或包含这些信息的日志。
