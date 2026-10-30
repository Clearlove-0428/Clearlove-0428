<p align="center">
  <img src="assets/header.svg" alt="Clearlove-0428 · 网络安全学习与本地工具开发" width="100%">
</p>

<p align="center">
  <strong>西北工业大学在读 · 网络安全学习与工程实践</strong>
</p>

<p align="center">
  <a href="#安全学习与工具实践">安全学习</a> ·
  <a href="#已经公开的项目">公开项目</a> ·
  <a href="#项目中的技术">项目技术</a>
</p>

我关注学习和日常使用中反复遇到的问题：把分散通知整理成日程，把课堂资料变成便于回查的文件，把重复分析步骤写成可复现的工具。目前主要从 CTF、Linux 实验和本地软件项目继续打基础。

项目在 AI 辅助下持续迭代，仓库保留源码、使用说明、测试入口和已知限制。

## 安全学习与工具实践

**CTF 离线工具箱 · 正在整理公开版本**

本地 v1.0.0 已整理 41 项工具能力及中文手册，覆盖字节与编码、密码学基础、文件与图片分析、流量分析及离线 Web / Reverse 辅助分析。2026 年 10 月的本地验收记录包含 113 项单元测试、86 条命令检查和 5 条跨工具流程；源码与公开示例正在整理。

**Linux 排查实验 · 本地项目**

围绕状态快照、前后差异、编号证据和时间线开展练习，并尝试用 Agent Skill 组织只读排查流程，逐项核对自动提示与原始证据。

## 已经公开的项目

| 项目 | 做什么 · 可以查看什么 |
| :--- | :--- |
| **[拾光 Shiguang](https://github.com/Clearlove-0428/shiguang)** | 本地通知整理与日程提醒。支持规则和可选本地模型、原文核对、日程确认及提醒重试。提供运行截图、架构说明和验证记录。<br><br>[项目介绍](https://github.com/Clearlove-0428/shiguang#readme) · [架构](https://github.com/Clearlove-0428/shiguang/blob/main/docs/architecture.md) · [验证](https://github.com/Clearlove-0428/shiguang/blob/main/docs/validation.md) · [自动测试](https://github.com/Clearlove-0428/shiguang/actions) |
| **[雨课堂课件导出](https://github.com/Clearlove-0428/yuketang-slide-export)** | 将账号可见的课堂课件图片整理为 PDF，保留播放顺序和页码映射，支持像素去重与失败续跑。提供合成图片和模拟接口测试。<br><br>[运行方法](https://github.com/Clearlove-0428/yuketang-slide-export#readme) · [测试代码](https://github.com/Clearlove-0428/yuketang-slide-export/blob/main/test_export.py) · [自动测试](https://github.com/Clearlove-0428/yuketang-slide-export/actions) |
| **[启翔湖畔资料工具](https://github.com/Clearlove-0428/qixiang-channel-toolkit)** | 本机资料库、跨批去重、人工复核、统计导出与离线浏览。保留观察来源和复核依据，公开版本附虚构示例。<br><br>[项目介绍](https://github.com/Clearlove-0428/qixiang-channel-toolkit#readme) · [验证记录](https://github.com/Clearlove-0428/qixiang-channel-toolkit/blob/main/docs/%E9%AA%8C%E8%AF%81%E7%8A%B6%E6%80%81.md) · [虚构示例](https://github.com/Clearlove-0428/qixiang-channel-toolkit/tree/main/examples) |

## 项目中的技术

`Python` `JavaScript` `Node.js` `SQLite` `PowerShell` `C# / WebView2`

这些项目涉及命令行工具、本地网页与 Windows 界面、数据持久化、任务队列、自动测试和 GitHub Actions。当前继续学习 Linux、CTF 基础与代码阅读，并补充不同设备上的实测记录。

---

<p align="center"><sub>源码、说明与验证记录持续更新。</sub></p>
