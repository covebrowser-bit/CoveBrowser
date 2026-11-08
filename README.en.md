<div align="center">

<img src="docs/assets/logo.png" width="72" alt="Cove Browser fingerprint browser" />

# Cove Browser

**Fingerprint browser for cross-border e-commerce£üIsolated stores ¡¤ Proxies ¡¤ Window sync**

[English](./README.en.md) ¡¤ [ÖÐÎÄ](./README.md)

<p>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/download-Windows%20%7C%20macOS-0A7CFF.svg" alt="Download"></a>
  <a href="https://github.com/covebrowser-bit/CoveBrowser/stargazers"><img src="https://img.shields.io/github/stars/covebrowser-bit/CoveBrowser?style=flat" alt="Stars"></a>
  <a href="https://github.com/covebrowser-bit/CoveBrowser/issues"><img src="https://img.shields.io/github/issues/covebrowser-bit/CoveBrowser" alt="Issues"></a>
</p>

Desktop client for cross-border sellers and ops teams ¡ª isolate **Amazon / Shopify / Shopee / TikTok Shop** and other storefronts, bind proxies, and sync windows for bulk work.

**Download** ¡ú [covebrowser.com](https://covebrowser.com/) (Windows ¡¤ macOS)£üCurrent **v0.1.14**

</div>

<p align="center">
  <img src="docs/assets/website-hero.png" width="900" alt="Cove Browser website and environment manager for ecommerce" />
</p>

---

## Contents

- [Detection sites](#detection-sites)
- [Use cases](#use-cases)
- [Features](#features)
- [Screenshots](#screenshots)
- [Get started](#get-started)
- [Contact](#contact)
- [Star History](#star-history)

---

## Detection sites

Profiles present as **Chrome** (UA / Client Hints). Public third-party samples ¡ª retest yourself.

| Detector | Focus | Summary |
|---|---|---|
| [Fingerprint.com](https://demo.fingerprint.com/) | Bot / VPN / tampering / VM | Bot, Tampering Not detected |
| [BrowserScan](https://www.browserscan.net/) | Identity, timezone, language, WebRTC | Chrome profile, top-tier authenticity |
| [bot.sannysoft.com](https://bot.sannysoft.com/) | WebDriver, Chrome, plugins, WebGL | Intoli-style checks passed / ok |
| [ScrapingCourse Antibot](https://www.scrapingcourse.com/antibot-challenge) | Antibot challenge | Bypassed |
| [DeviceAndBrowserInfo](https://deviceandbrowserinfo.com/) | isBot / WebDriver / Headless | You are human |

<details>
<summary><strong>Show detection screenshots</strong></summary>

<p align="center">
  <img src="docs/assets/detect-fingerprint-pro.png" width="900" alt="Fingerprint.com detection sample" />
</p>
<p align="center"><em>Fingerprint.com: Bot / Tampering / VM not detected</em></p>

<p align="center">
  <img src="docs/assets/detect-browserscan-detail.png" width="900" alt="BrowserScan authenticity 100%" />
</p>
<p align="center"><em>BrowserScan: fingerprint authenticity at top tier</em></p>

<p align="center">
  <img src="docs/assets/detect-browserscan.png" width="900" alt="BrowserScan Chrome identity" />
</p>
<p align="center"><em>BrowserScan overview: normal Chrome presentation</em></p>

<p align="center">
  <img src="docs/assets/detect-sannysoft.png" width="720" alt="Sannysoft WebDriver passed" />
</p>
<p align="center"><em>bot.sannysoft.com: WebDriver missing and related checks</em></p>

<p align="center">
  <img src="docs/assets/detect-antibot.png" width="720" alt="ScrapingCourse Antibot bypassed" />
</p>
<p align="center"><em>ScrapingCourse Antibot Challenge: bypassed</em></p>

<p align="center">
  <img src="docs/assets/detect-human.png" width="720" alt="DeviceAndBrowserInfo You are human" />
</p>
<p align="center"><em>DeviceAndBrowserInfo: You are human</em></p>

</details>

> Results vary by detector and setup. Retest with region-matched proxy before go-live.

---

## Use cases

Sellers worry about **linked stores** and **shared browsers causing account bleed**. Cove Browser isolates each store/account ¡ª fingerprint, cookies, storage, proxy egress ¡ª from solo sellers to agencies.

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="Multi-store isolation for cross-border ecommerce" />
  &nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="Social matrix account isolation" />
</p>

### Multi-marketplace, multi-store ops

Amazon, Shopify, eBay, Shopee, Lazada, Walmart, TikTok Shop, and more. Bind each store to its own environment and regional proxy so backend work stays isolated.

### Store registration and warm-up

Keep consistent fingerprint and egress IP through signup, review, and early growth ¡ª better for batch store opening.

### Ads and reporting consoles

Open Meta / Google / on-platform ad accounts in separate environments; window sync for budgets, reports, and campaign toggles.

### Social and private-domain matrices

Isolate Facebook, Instagram, TikTok, YouTube, WhatsApp, and email tools so publishing and DMs can run in parallel.

### Agencies and studio collaboration

Group by client ¡Á store, assign visibility and roles, hand off without rebuilding fingerprints and proxies.

### Local automation and batch jobs

Enable the local API inside an environment; after launch you get CDP for repricing, scraping, or listing scripts.

---

## Features

| Feature | Notes |
|---|---|
| Multi-account environments | Isolated fingerprint, cookies, storage, proxy |
| Batch ops | Create, import, start, stop, recycle bin |
| Groups & tags | By project / client / owner |
| Window sync | Mouse, keyboard, scroll across windows |
| Local API | Localhost JSON API; CDP after launch |
| Team collaboration | Members, roles, permissions |
| Proxies | HTTP / HTTPS / SOCKS5 with checks |

---

## Screenshots

Desktop UI (v0.1.x).

### Environment manager

<p align="center">
  <img src="docs/assets/profiles.png" width="900" alt="Cove Browser multi-store environment manager" />
</p>

### Fingerprint settings

<p align="center">
  <img src="docs/assets/fingerprint.png" width="900" alt="Cove Browser Canvas WebGL Audio fingerprint settings" />
</p>

### Launch progress

<p align="center">
  <img src="docs/assets/launch.png" width="720" alt="Cove Browser environment launch progress" />
</p>

---

## Get started

1. Download from [covebrowser.com](https://covebrowser.com/) (Windows / macOS)  
2. Sign in with email  
3. Create an environment (fingerprint, proxy, notes)  
4. Launch; enable the local API when you need automation  

---

## Contact

- Website: [covebrowser.com](https://covebrowser.com/)
- Email: [support@covebrowser.com](mailto:support@covebrowser.com)
- Telegram: [@covebrowser](https://t.me/covebrowser)
- Issues: [covebrowser-bit/CoveBrowser](https://github.com/covebrowser-bit/CoveBrowser/issues)

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=covebrowser-bit/CoveBrowser&type=Date)](https://star-history.com/#covebrowser-bit/CoveBrowser&Date)

---

<sub>MIT License ¡¤ Product docs & screenshots ¡¤ Installers from the website</sub>
