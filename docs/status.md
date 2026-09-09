# 开发与平台状态

更新日期：2026-09-09。

当前处于开发与试点准备阶段，已实现项目/对话办案、材料分类和原文引用、事实修正、分析与起草、版本复核、DOCX/PDF 导出，以及后台统一模型与账号管理。

| 平台 | 已知状态 |
| --- | --- |
| macOS Apple Silicon | 已有真实 Electron、模型分析、OCR、片段改写及本地打包验证；本地测试包不等于公开签名/公证发行包 |
| Windows x64 | 真实 Windows runner 上源应用 OAuth/案件检查 6 项、打包应用 OAuth 检查 1 项通过；提供未签名 NSIS/便携试点包，用户机器安装及 Word/WPS 排版兼容性待验收 |
| Linux | 保留 AppImage 构建能力，律所工作流尚无本轮真机验证记录 |

账号站点提供邀请激活、密码找回、用户中心与运营后台。v0.1.0-beta.35 桌面改用系统浏览器授权；macOS 已验证账号切换、令牌刷新、设备撤销和原案件恢复。Windows 已通过独立 Windows runner 的源应用和打包应用 OAuth 检查、打包运行依赖与公共内容审计，以及安装附件未签名状态和哈希校验；这些结果不代替用户机器安装或 Word/WPS 的试点验收。模型可用性取决于管理员配置的服务。尚未发行的版本不能通过历史验证记录推定可用。

团队同步、共享知识库、多级审批、客户门户、权威法规/案例库接入和支付尚未完成。法律实质质量、真实卷宗适用性和节省工时仍需律师试点评估。

发行记录以本仓库 [Releases](https://github.com/CBx-2023/Melatonin-Releases/releases) 为准。已提供 v0.1.0-beta.35 的 macOS Apple Silicon 测试包（ad-hoc 签名，未公证）和 Windows x64 NSIS/便携试点包（未签名）；Windows 使用独立的 `SHA256SUMS-Windows.txt` 校验文件，原 macOS 附件与校验文件保持不变。Intel Mac 与 Linux 安装包尚未发行。
