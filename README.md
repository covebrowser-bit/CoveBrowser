<div align="center">

<img src="docs/assets/logo.png" width="80" alt="Cove Browser" />

# Cove Browser

### 免费跨境电商指纹浏览器平台

**一店一环境 · 防关联 · 开箱即用**

独立指纹 / Cookie / 代理出口，降低多店牵连与团队串号  
窗口同步批量操作，多平台开店、养号、投放一套搞定

<br/>

[English](./README.en.md) · [中文](./README.md)

<br/>

<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/%E5%85%8D%E8%B4%B9%E5%B9%B3%E5%8F%B0-Free-22C55E?style=for-the-badge" alt="免费平台" /></a>
&nbsp;
<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/Download-Windows%20%7C%20macOS-0A7CFF?style=for-the-badge" alt="下载客户端" /></a>
&nbsp;
<a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT" /></a>

<br/><br/>

**免费下载** → [covebrowser.com](https://covebrowser.com/)　｜　当前版本 **v0.1.14**

</div>

<br/>

| 免费上手 | 强隔离 | 更高效率 |
|:---:|:---:|:---:|
| 客户端免费下载，注册即用 | 指纹 · Cookie · 代理出口按店分开 | 窗口同步 + 本地 API / CDP |

---

## 目录

- [平台介绍](#平台介绍)
- [各网站检测结果](#各网站检测结果)
- [应用场景](#应用场景)
- [快速上手](#快速上手)
- [联系我们](#联系我们)

---

## 平台介绍

Cove Browser 是面向跨境卖家、代运营与团队协作的**免费指纹浏览器平台**。  
围绕 Amazon、Shopify、Shopee、TikTok Shop 等站点，为每个店铺建立独立运行环境——指纹、Cookie、本地存储与代理出口完全分开，支持开店养号、窗口同步与本地自动化，降低多店关联与团队串号风险。

### 为什么做免费平台

跨境卖家真正刚需的是：**多店隔离、稳定可用、团队能协作**。但市面上不少指纹浏览器把这些能力绑在高价套餐上——按环境数、席位或窗口数收费，店铺一多、团队一扩，成本就跟着翻倍。

常见结果是：

| 现状 | 带来的问题 |
|---|---|
| **按环境 / 席位收费** | 多开几个店、多加几个人，月费快速上涨 |
| **功能被套餐卡住** | 窗口同步、团队权限、API 等能力拆成付费档 |
| **成本高于工具价值** | 小卖家、工作室把预算耗在浏览器上，而不是投放与货盘 |
| **仍要承担运营风险** | 花了钱，店铺关联、Cookie 串号、代理错配一样可能发生 |

我们做 Cove Browser，就是想把「多账号独立环境」这件事做成**可免费上手的平台**：先解决隔离与协作，再把精力留给真正赚钱的业务。客户端官网免费下载，注册即可开始使用。

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

卖家与团队最怕三件事：**店铺互相牵连**、**多人共用浏览器串号**、**工具月费比利润涨得还快**。  
Cove Browser 把每个店铺 / 账号做成独立环境，把隔离能力做成免费平台，让个人卖家、代运营与工作室都能直接上手。

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="多店铺隔离" />
  &nbsp;&nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="社媒矩阵隔离" />
</p>

| 场景 | 痛点 | Cove 怎么做 |
|---|---|---|
| **多平台多店铺运营** | 多店同机登录易关联；商业指纹浏览器按环境收费，店越多越贵 | 一店一环境 + 地区代理；免费平台起步，后台、上架、履约互不干扰 |
| **新店注册与养号** | 设备画像不稳、IP 乱跳，过审与养号反复失败 | 注册到日常浏览保持一致指纹与出口 IP，适合批量建店 |
| **广告投放与数据看板** | 多广告户切号清缓存耗时，误用同一浏览器易牵连 | 分环境打开 Meta / Google / 站内广告户，窗口同步改预算、查报表 |
| **社媒与私域矩阵** | Cookie 串号导致账号互相关联，矩阵号批量异常 | Facebook、Instagram、TikTok、YouTube、WhatsApp 等各自隔离 |
| **代运营 / 企业协作** | 席位费叠加；新人接手要重配指纹和代理 | 按「客户 × 店铺」分组授权，环境库统一维护 |
| **本地自动化** | 自动化要另购高价 API / 自动化档，成本再抬一截 | 本机 API + CDP，在指定环境内对接改价、采集、上架 |

---

## 快速上手

| 步骤 | 操作 |
|:---:|---|
| 1 | 打开 [covebrowser.com](https://covebrowser.com/) **免费下载**客户端（Windows / macOS） |
| 2 | 邮箱注册 / 登录 |
| 3 | 创建环境：配置指纹、代理、备注 |
| 4 | 启动环境开始工作；需要自动化时再开启本地 API |

<div align="center">

<br/>

**免费开始** → [下载 Cove Browser](https://covebrowser.com/)

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
<sub>MIT License · 免费平台 · 安装包请从官网获取</sub>
</div>
