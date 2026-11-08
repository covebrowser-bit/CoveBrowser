<div align="center">

<img src="docs/assets/logo.png" width="72" alt="Cove Browser" />

# Cove Browser

**面向跨境电商的指纹浏览器桌面客户端**

[English](./README.en.md) · [中文](./README.md)

给跨境电商卖家和运营团队用——多店铺、多站点各自独立环境，配好代理就能开店养号、窗口同步批量操作，不用自己拼命令行。

- 官网下载：[covebrowser.com](https://covebrowser.com/)（Windows · macOS）
- 当前客户端：**Cove Browser v0.1.14**

</div>

---

## 目录

- [官网](#官网)
- [软件截图](#软件截图)
- [能做什么](#能做什么)
- [检测示例](#检测示例)
- [四步上手](#四步上手)
- [仓库说明](#仓库说明)
- [联系我们](#联系我们)
- [Star History](#star-history)

---

## 官网

[covebrowser.com](https://covebrowser.com/) 是产品主页：介绍独立环境、指纹隔离、代理绑定、窗口同步与团队协作，并提供安装包下载。

<p align="center">
  <img src="docs/assets/website-hero.png" width="900" alt="Cove Browser 官网与桌面客户端预览" />
</p>

<p align="center"><em>官网首页：产品介绍 + 客户端环境管理界面</em></p>

---

## 软件截图

下面是桌面客户端主要功能界面（v0.1.x）。

### 环境管理

给每个账号建独立环境：指纹、代理、分组、备注分开存放。启动、编辑、分享、删除都在这一页。

<p align="center">
  <img src="docs/assets/profiles.png" width="900" alt="Cove Browser 环境管理" />
</p>

### 指纹配置

按环境配置 Canvas / WebGL / Audio / 硬件与系统参数，账号之间不共用一套设备特征。

<p align="center">
  <img src="docs/assets/fingerprint.png" width="900" alt="Cove Browser 指纹配置" />
</p>

### 启动环境

打开环境时显示启动进度；内核与代理就绪后进入独立浏览器窗口。

<p align="center">
  <img src="docs/assets/launch.png" width="720" alt="Cove Browser 启动进度" />
</p>

### 适用场景

多店铺、社媒矩阵等场景可按环境隔离 Cookie、指纹与出口网络。

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="多店铺场景" />
  &nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="社媒场景" />
</p>

---

## 能做什么

| 功能 | 说明 |
|---|---|
| 多账号环境 | 每个环境独立指纹、Cookie、存储和代理 |
| 批量管理 | 创建、导入、启动、停止、回收站 |
| 分组与标签 | 按项目、客户或负责人整理环境 |
| 窗口同步 | 主控窗口的鼠标、键盘、滚动同步到多个从窗口 |
| 本地 API | 本机 JSON API，可对接自动化；打开环境后返回 CDP |
| 团队协作 | 成员、角色、权限、环境分配 |
| 代理 | HTTP / HTTPS / SOCKS5 等，保存、检测、绑定到环境 |

内核侧按 **Chrome** 身份呈现（UA / Client Hints），检测站按普通 Chrome 评分，而不是未知浏览器。

---

## 检测示例

公开检测站结果可自行核对（示例截图）：

<p align="center">
  <img src="docs/assets/detect-fingerprint.webp" width="720" alt="Fingerprint 检测示例" />
</p>

<p align="center">
  <img src="docs/assets/detect-browserscan.png" width="720" alt="BrowserScan 检测示例" />
</p>

---

## 四步上手

1. 打开 [covebrowser.com](https://covebrowser.com/) 下载客户端  
2. 用邮箱登录（个人或团队都可以）  
3. 创建环境：指纹、代理、备注  
4. 打开环境开始工作；需要自动化再开本地 API  

---

## 仓库说明

| | 本仓库 |
|---|---|
| 内容 | README、许可证、功能说明与截图 |
| 不包含 | Electron 源码、Chromium 指纹内核、服务端与密钥 |
| 安装包 | 请从官网下载，不以源码形式随仓库分发 |

---

## 联系我们

- 官网：[covebrowser.com](https://covebrowser.com/)
- 邮箱：[support@covebrowser.com](mailto:support@covebrowser.com)
- Telegram：[@covebrowser](https://t.me/covebrowser)
- QQ 群：`263172684`
- Issues：[covebrowser-bit/CoveBrowser](https://github.com/covebrowser-bit/CoveBrowser/issues)

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=covebrowser-bit/CoveBrowser&type=Date)](https://star-history.com/#covebrowser-bit/CoveBrowser&Date)
