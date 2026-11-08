<div align="center">

<img src="docs/assets/logo.png" width="80" alt="Cove Browser" />

# Cove Browser

### 跨境电商指纹浏览器平台

为每个店铺建立独立浏览器环境，隔离指纹 · Cookie · 代理出口  
降低多店关联与团队串号风险

<br/>

[English](./README.en.md) · [中文](./README.md)

<br/>

<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/Website-covebrowser.com-0A7CFF?style=for-the-badge" alt="官网" /></a>
&nbsp;
<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/Download-Windows%20%7C%20macOS-111827?style=for-the-badge" alt="下载客户端" /></a>
&nbsp;
<a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT" /></a>

<br/><br/>

**官网下载** → [covebrowser.com](https://covebrowser.com/)　｜　当前版本 **v0.1.14**

</div>

<br/>

| 多店隔离 | 团队协作 | 批量效率 |
|:---:|:---:|:---:|
| 一店一环境，指纹与出口 IP 分离 | 成员权限、环境分配、统一管理 | 窗口同步 + 本地 API / CDP |

---

## 目录

- [平台介绍](#平台介绍)
- [各网站检测结果](#各网站检测结果)
- [应用场景](#应用场景)
- [快速上手](#快速上手)
- [联系我们](#联系我们)

---

## 平台介绍

Cove Browser 是面向**跨境卖家、代运营与企业团队**的桌面指纹浏览器平台。  
围绕 Amazon、Shopify、Shopee、TikTok Shop 等电商站点，把每个店铺做成独立运行环境——指纹、Cookie、本地存储与代理出口完全分开，支持开店养号、窗口同步与本地自动化。

<p align="center">
  <img src="docs/assets/website-hero.png" width="920" alt="Cove Browser 平台官网与环境管理" />
</p>

### 平台能力

| | 能力 | 说明 |
|:---:|---|---|
| 01 | **多账号环境** | 每环境独立指纹、Cookie、存储与代理 |
| 02 | **批量管理** | 创建、导入、启动、停止、回收站一站完成 |
| 03 | **分组与标签** | 按项目、客户、负责人整理环境库 |
| 04 | **窗口同步** | 鼠标、键盘、滚动同步到多窗口 |
| 05 | **本地 API** | 本机 JSON API，启动后返回 CDP |
| 06 | **团队协作** | 成员、角色、权限与环境分配 |
| 07 | **代理管理** | HTTP / HTTPS / SOCKS5，检测后绑定环境 |

### 客户端界面

<p align="center">
  <img src="docs/assets/profiles.png" width="900" alt="环境管理" />
</p>
<p align="center"><sub>环境管理 — 店铺、指纹、代理、分组与备注集中维护</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/fingerprint.png" width="900" alt="指纹配置" />
</p>
<p align="center"><sub>指纹配置 — Canvas / WebGL / Audio / 硬件与系统参数按环境隔离</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/launch.png" width="720" alt="启动环境" />
</p>
<p align="center"><sub>启动环境 — 内核与代理就绪后进入独立浏览器窗口</sub></p>

---

## 各网站检测结果

内核以 **Chrome** 身份呈现（UA / Client Hints）。以下为公开第三方检测站实测摘要，便于自行复测。

| 检测站 | 关注点 | 结果 |
|---|---|:---:|
| [Fingerprint.com](https://demo.fingerprint.com/) | Bot / VPN / 篡改 / 虚拟机 | **Not detected** |
| [BrowserScan](https://www.browserscan.net/) | 身份、时区、语言、WebRTC、可信度 | **真实性满分档** |
| [bot.sannysoft.com](https://bot.sannysoft.com/) | WebDriver、Chrome、插件、WebGL | **Passed** |
| [ScrapingCourse Antibot](https://www.scrapingcourse.com/antibot-challenge) | Antibot 挑战 | **通过** |
| [DeviceAndBrowserInfo](https://deviceandbrowserinfo.com/) | isBot / WebDriver / Headless | **You are human** |

<details>
<summary><b>展开检测截图</b></summary>

<br/>

<p align="center">
  <img src="docs/assets/detect-fingerprint-pro.png" width="900" alt="Fingerprint.com" />
</p>
<p align="center"><sub>Fingerprint.com — Bot / Tampering / VM 等未检出</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-browserscan-detail.png" width="900" alt="BrowserScan" />
</p>
<p align="center"><sub>BrowserScan — Browser fingerprint authenticity 满分档</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-sannysoft.png" width="720" alt="Sannysoft" />
</p>
<p align="center"><sub>bot.sannysoft.com — WebDriver missing 等项通过</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-antibot.png" width="720" alt="Antibot" />
</p>
<p align="center"><sub>ScrapingCourse Antibot Challenge — 通过</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-human.png" width="720" alt="DeviceAndBrowserInfo" />
</p>
<p align="center"><sub>DeviceAndBrowserInfo — You are human</sub></p>

</details>

> 检测结果随站点算法与配置变化。正式开店前，请用目标地区代理 + 对应环境再测一轮。

---

## 应用场景

卖家与企业团队最怕两件事：**店铺互相牵连**，以及**多人共用浏览器导致串号**。  
Cove Browser 把每个店铺 / 账号做成独立环境——指纹、Cookie、本地存储、代理出口分开，从个人卖家到代运营、工作室都能直接上手。

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="多店铺隔离" />
  &nbsp;&nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="社媒矩阵隔离" />
</p>

| 场景 | 怎么用 |
|---|---|
| **多平台多店铺运营** | Amazon、Shopify、eBay、Shopee、Lazada、Walmart、TikTok Shop 等，一店一环境 + 地区代理，后台、上架、履约互不干扰 |
| **新店注册与养号** | 注册、过审、养权重保持一致指纹与出口 IP，适合批量建店与长期维护 |
| **广告投放与数据看板** | Meta / Google / 站内广告账户分环境打开，窗口同步改预算、查报表、开关活动 |
| **社媒与私域矩阵** | Facebook、Instagram、TikTok、YouTube、WhatsApp 等账号隔离，发布与私信可并行 |
| **代运营 / 企业协作** | 按「客户 × 店铺」分组与授权，环境库统一维护，新人接手无需重配 |
| **本地自动化** | 开启本机 API，在指定环境内对接改价、采集、上架；启动后返回 CDP |

---

## 快速上手

| 步骤 | 操作 |
|:---:|---|
| 1 | 打开 [covebrowser.com](https://covebrowser.com/) 下载客户端（Windows / macOS） |
| 2 | 邮箱登录（个人或团队账号） |
| 3 | 创建环境：配置指纹、代理、备注 |
| 4 | 启动环境开始工作；需要自动化时再开启本地 API |

<div align="center">

<br/>

**现在开始** → [下载 Cove Browser](https://covebrowser.com/)

</div>

---

## 联系我们

| | |
|---|---|
| 官网 | [covebrowser.com](https://covebrowser.com/) |
| 邮箱 | [support@covebrowser.com](mailto:support@covebrowser.com) |
| Telegram | [@covebrowser](https://t.me/covebrowser) |
| QQ 群 | `263172684` |
| Issues | [covebrowser-bit/CoveBrowser](https://github.com/covebrowser-bit/CoveBrowser/issues) |

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=covebrowser-bit/CoveBrowser&type=Date)](https://star-history.com/#covebrowser-bit/CoveBrowser&Date)

---

<div align="center">
<sub>MIT License · 安装包请从官网获取</sub>
</div>
