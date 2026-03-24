<p align="center">
  <img src="public/images/logo-brand.png" width="360" alt="maynoraiclawpanel">
</p>

<p align="center">
  内置 AI 助手的 OpenClaw 管理面板 — 一键安装、配置、诊断、修复
</p>

<p align="center">
  <a href="https://github.com/xianyu110/maynorai-clawpanel/releases/latest">
    <img src="https://img.shields.io/github/v/release/xianyu110/maynorai-clawpanel?style=flat-square&color=6366f1" alt="Release">
  </a>
  <a href="https://github.com/xianyu110/maynorai-clawpanel/releases/latest">
    <img src="https://img.shields.io/github/downloads/xianyu110/maynorai-clawpanel/total?style=flat-square&color=8b5cf6" alt="Downloads">
  </a>
  <a href="https://github.com/xianyu110/maynorai-clawpanel/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-green.svg?style=flat-square" alt="License">
  </a>
</p>

---

<p align="center">
  <a href="https://www.tryopenclaw.asia/download.html">
    <img src="https://img.shields.io/badge/%F0%9F%93%A5%20%E4%B8%8B%E8%BD%BD%E5%AE%89%E8%A3%85%E5%8C%85-%E7%82%B9%E5%87%BB%E8%8E%B7%E5%8F%96-6366f1?style=for-the-badge" alt="下载安装">
  </a>
</p>

ClawPanel 是 OpenClaw AI Agent 框架的可视化管理面板。内置智能 AI 助手，帮你一键安装 OpenClaw、自动诊断配置、排查问题、修复错误。

> 🌐 **官网**: [www.tryopenclaw.asia](https://www.tryopenclaw.asia)  |  📦 **下载**: [www.tryopenclaw.asia/download.html](https://www.tryopenclaw.asia/download.html)

## 下载安装

前往 [下载页面](https://www.tryopenclaw.asia/download.html) 获取最新版本安装包。

### 安装包说明

| 后缀 | 系统 |
|------|------|
| aarch64.dmg | macOS M芯片 (M1/M2/M3/M4) |
| x64.dmg | macOS Intel |
| exe / msi | Windows |
| AppImage / deb / rpm | Linux |

## Docker 部署

```bash
docker run -d   --name clawpanel   --restart unless-stopped   -p 1420:1420   -p 18789:18789   -v clawpanel-data:/root/.openclaw   -e ACCESS_PASSWORD=123456   maynorai/maynoraiclawpanel:latest
```

访问 http://localhost:1420，默认密码: 123456

## 更多信息

- 完整文档: [GitHub README](https://github.com/xianyu110/maynorai-clawpanel#readme)
- 问题反馈: [GitHub Issues](https://github.com/xianyu110/maynorai-clawpanel/issues)
- 许���证: CC BY-NC-SA 4.0 (仅限非商业用途)
