<div align="center">

<img src="docs/assets/logo.png" width="72" alt="Cove Browser 指纹浏览器" />

# Cove Browser

**跨境电商指纹浏览器｜多店铺独立环境 · 代理绑定 · 窗口同步**

[English](./README.en.md) · [中文](./README.md)

<p>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/download-Windows%20%7C%20macOS-0A7CFF.svg" alt="Download"></a>
  <a href="https://github.com/covebrowser-bit/CoveBrowser/stargazers"><img src="https://img.shields.io/github/stars/covebrowser-bit/CoveBrowser?style=flat" alt="Stars"></a>
  <a href="https://github.com/covebrowser-bit/CoveBrowser/issues"><img src="https://img.shields.io/github/issues/covebrowser-bit/CoveBrowser" alt="Issues"></a>
</p>

给跨境电商卖家和运营团队用的桌面客户端——**Amazon / Shopify / Shopee / TikTok Shop** 等多平台多店铺各自独立环境，配好代理就能开店养号、窗口同步批量操作。

**立即下载** → [covebrowser.com](https://covebrowser.com/)（Windows · macOS）｜当前版本 **v0.1.14**

</div>

<p align="center">
  <img src="docs/assets/website-hero.png" width="900" alt="Cove Browser 跨境电商指纹浏览器官网与环境管理界面" />
</p>

---

## 目录

- [检测通过的网站](#检测通过的网站)
- [应用场景](#应用场景)
- [功能说明](#功能说明)
- [软件截图](#软件截图)
- [快速上手](#快速上手)
- [联系我们](#联系我们)
- [Star History](#star-history)

---

## 检测通过的网站

内核按 **Chrome** 身份呈现（UA / Client Hints）。以下为公开第三方检测站实测示例，可自行复测。

| 检测站 | 关注点 | 结果摘要 |
|---|---|---|
| [Fingerprint.com](https://demo.fingerprint.com/) | Bot / VPN / 篡改 / 虚拟机 | Bot、Tampering 等 Not detected |
| [BrowserScan](https://www.browserscan.net/) | 身份、时区、语言、WebRTC、可信度 | Chrome 画像，真实性满分档 |
| [bot.sannysoft.com](https://bot.sannysoft.com/) | WebDriver、Chrome、插件、WebGL | Intoli 系多项 passed / ok |
| [ScrapingCourse Antibot](https://www.scrapingcourse.com/antibot-challenge) | Antibot 挑战 | 挑战通过 |
| [DeviceAndBrowserInfo](https://deviceandbrowserinfo.com/) | isBot / WebDriver / Headless | You are human |

<details>
<summary><strong>展开查看检测截图</strong></summary>

<p align="center">
  <img src="docs/assets/detect-fingerprint-pro.png" width="900" alt="Fingerprint.com 指纹浏览器检测结果" />
</p>
<p align="center"><em>Fingerprint.com：Bot / Tampering / VM 等未检出</em></p>

<p align="center">
  <img src="docs/assets/detect-browserscan-detail.png" width="900" alt="BrowserScan 指纹真实性 100%" />
</p>
<p align="center"><em>BrowserScan：Browser fingerprint authenticity 满分档</em></p>

<p align="center">
  <img src="docs/assets/detect-sannysoft.png" width="720" alt="Sannysoft WebDriver 检测通过" />
</p>
<p align="center"><em>bot.sannysoft.com：WebDriver missing 等项通过</em></p>

<p align="center">
  <img src="docs/assets/detect-antibot.png" width="720" alt="ScrapingCourse Antibot 挑战通过" />
</p>
<p align="center"><em>ScrapingCourse Antibot Challenge：通过</em></p>

<p align="center">
  <img src="docs/assets/detect-human.png" width="720" alt="DeviceAndBrowserInfo You are human" />
</p>
<p align="center"><em>DeviceAndBrowserInfo：You are human</em></p>

</details>

> 检测结果随站点算法与配置变化；正式开店前请用目标地区代理 + 对应环境再测一轮。

---

## 应用场景

跨境卖家最怕两件事：**店铺互相牵连**，以及**团队共用浏览器导致串号**。Cove Browser 把每个店铺 / 账号做成独立环境——指纹、Cookie、本地存储、代理出口分开，覆盖个人卖家到代运营团队。

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="跨境电商多店铺指纹隔离场景" />
  &nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="社媒矩阵账号隔离场景" />
</p>

### 多平台多店铺运营

Amazon、Shopify、eBay、Shopee、Lazada、Walmart、TikTok Shop 等，一个卖家常同时管理几十上百个店。每个店铺绑定独立环境 + 地区代理，后台登录、上架改价、履约互不干扰，降低「一号异常、全店受影响」的风险。

### 新店注册与养号

开店、过审、养权重需要稳定的设备与网络画像。为注册、登录、日常浏览规划环境，让账号长期保持一致的指纹与出口 IP，更适合批量建店与长期维护。

### 广告投放与数据看板

多套 Meta / Google / 站内广告账户用独立环境打开，配合窗口同步批量改预算、查报表、开关活动，减少切号与清缓存成本。

### 社媒与私域矩阵

Facebook、Instagram、TikTok、YouTube、WhatsApp、邮件工具等矩阵账号各自隔离，发布、私信、社群可并行，避免 Cookie 串号关联。

### 代运营 / 工作室协作

按「客户 × 店铺」分组，分配成员可见范围与权限。环境库统一维护，新人接手不必重配指纹和代理。

### 本地自动化与批量任务

开启本机 API，在指定环境内对接改价、采集、上架脚本；启动后可返回 CDP，把隔离环境与自动化接在同一链路。

---

## 功能说明

| 功能 | 说明 |
|---|---|
| 多账号环境 | 每环境独立指纹、Cookie、存储、代理 |
| 批量管理 | 创建、导入、启动、停止、回收站 |
| 分组与标签 | 按项目、客户、负责人整理 |
| 窗口同步 | 鼠标、键盘、滚动同步到多窗口 |
| 本地 API | 本机 JSON API，启动后返回 CDP |
| 团队协作 | 成员、角色、权限、环境分配 |
| 代理管理 | HTTP / HTTPS / SOCKS5，检测并绑定环境 |

---

## 软件截图

桌面客户端界面（v0.1.x）。

### 环境管理

<p align="center">
  <img src="docs/assets/profiles.png" width="900" alt="Cove Browser 多店铺环境管理界面" />
</p>

### 指纹配置

<p align="center">
  <img src="docs/assets/fingerprint.png" width="900" alt="Cove Browser Canvas WebGL Audio 指纹配置" />
</p>

### 启动环境

<p align="center">
  <img src="docs/assets/launch.png" width="720" alt="Cove Browser 环境启动进度" />
</p>

---

## 快速上手

1. 打开 [covebrowser.com](https://covebrowser.com/) 下载客户端（Windows / macOS）  
2. 邮箱登录（个人或团队）  
3. 创建环境：配置指纹、代理、备注  
4. 启动环境开始工作；需要自动化再开启本地 API  

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

---

<sub>MIT License · 产品文档与截图仓库 · 安装包请从官网获取</sub>
