<div align="center">

<img src="docs/assets/logo.png" width="80" alt="Cove Browser" />

# Cove Browser

### Fingerprint browser platform for cross-border e-commerce

Independent browser environments per storefront ！ fingerprint ， cookies ， proxy egress  
Reduce store linking and team account bleed

<br/>

[English](./README.en.md) ， [嶄猟](./README.md)

<br/>

<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/Website-covebrowser.com-0A7CFF?style=for-the-badge" alt="Website" /></a>
&nbsp;
<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/Download-Windows%20%7C%20macOS-111827?style=for-the-badge" alt="Download" /></a>
&nbsp;
<a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT" /></a>

<br/><br/>

**Download** ★ [covebrowser.com](https://covebrowser.com/)　��　Current **v0.1.14**

</div>

<br/>

| Store isolation | Team collaboration | Batch efficiency |
|:---:|:---:|:---:|
| One store, one environment | Roles, assignment, shared workspace | Window sync + local API / CDP |

---

## Contents

- [Platform](#platform)
- [Detection results](#detection-results)
- [Use cases](#use-cases)
- [Get started](#get-started)
- [Contact](#contact)

---

## Platform

Cove Browser is a desktop fingerprint-browser **platform** for **sellers, agencies, and business teams**.  
For Amazon, Shopify, Shopee, TikTok Shop and more, each storefront becomes an isolated runtime ！ fingerprint, cookies, storage, and proxy egress stay separate ！ with account warm-up, window sync, and local automation.

<p align="center">
  <img src="docs/assets/website-hero.png" width="920" alt="Cove Browser platform overview" />
</p>

### Platform capabilities

| | Capability | Notes |
|:---:|---|---|
| 01 | **Multi-account environments** | Isolated fingerprint, cookies, storage, proxy |
| 02 | **Batch ops** | Create, import, start, stop, recycle bin |
| 03 | **Groups & tags** | Organize by project / client / owner |
| 04 | **Window sync** | Mouse, keyboard, scroll across windows |
| 05 | **Local API** | Localhost JSON API; CDP after launch |
| 06 | **Team collaboration** | Members, roles, permissions, assignment |
| 07 | **Proxy management** | HTTP / HTTPS / SOCKS5 with checks |

### Client UI

<p align="center">
  <img src="docs/assets/profiles.png" width="900" alt="Environment manager" />
</p>
<p align="center"><sub>Environment manager ！ stores, fingerprints, proxies, groups, notes</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/fingerprint.png" width="900" alt="Fingerprint settings" />
</p>
<p align="center"><sub>Fingerprint settings ！ Canvas / WebGL / Audio / hardware isolated per profile</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/launch.png" width="720" alt="Launch progress" />
</p>
<p align="center"><sub>Launch ！ open an independent browser window when ready</sub></p>

---

## Detection results

Profiles present as **Chrome** (UA / Client Hints). Public third-party samples ！ retest yourself.

| Detector | Focus | Result |
|---|---|:---:|
| [Fingerprint.com](https://demo.fingerprint.com/) | Bot / VPN / tampering / VM | **Not detected** |
| [BrowserScan](https://www.browserscan.net/) | Identity, timezone, language, WebRTC | **Top-tier authenticity** |
| [bot.sannysoft.com](https://bot.sannysoft.com/) | WebDriver, Chrome, plugins, WebGL | **Passed** |
| [ScrapingCourse Antibot](https://www.scrapingcourse.com/antibot-challenge) | Antibot challenge | **Bypassed** |
| [DeviceAndBrowserInfo](https://deviceandbrowserinfo.com/) | isBot / WebDriver / Headless | **You are human** |

<details>
<summary><b>Show detection screenshots</b></summary>

<br/>

<p align="center">
  <img src="docs/assets/detect-fingerprint-pro.png" width="900" alt="Fingerprint.com" />
</p>
<p align="center"><sub>Fingerprint.com ！ Bot / Tampering / VM not detected</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-browserscan-detail.png" width="900" alt="BrowserScan" />
</p>
<p align="center"><sub>BrowserScan ！ fingerprint authenticity at top tier</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-sannysoft.png" width="720" alt="Sannysoft" />
</p>
<p align="center"><sub>bot.sannysoft.com ！ WebDriver missing and related checks</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-antibot.png" width="720" alt="Antibot" />
</p>
<p align="center"><sub>ScrapingCourse Antibot Challenge ！ bypassed</sub></p>

<br/>

<p align="center">
  <img src="docs/assets/detect-human.png" width="720" alt="DeviceAndBrowserInfo" />
</p>
<p align="center"><sub>DeviceAndBrowserInfo ！ You are human</sub></p>

</details>

> Results vary by detector and setup. Retest with a region-matched proxy before go-live.

---

## Use cases

Sellers and business teams worry about **linked stores** and **shared browsers causing account bleed**.  
Cove Browser turns every store or account into an isolated environment ！ fingerprint, cookies, storage, and proxy egress stay separate.

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="Multi-store isolation" />
  &nbsp;&nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="Social matrix isolation" />
</p>

| Scenario | How teams use it |
|---|---|
| **Multi-marketplace ops** | Amazon, Shopify, eBay, Shopee, Lazada, Walmart, TikTok Shop ！ one store, one environment + regional proxy |
| **Registration & warm-up** | Keep fingerprint and egress IP consistent through signup, review, and growth |
| **Ads & reporting** | Separate Meta / Google / on-platform ad accounts; window sync for budgets and reports |
| **Social & private-domain** | Isolate Facebook, Instagram, TikTok, YouTube, WhatsApp for parallel publishing and DMs |
| **Agencies & business teams** | Group by client 〜 store with roles; hand off without rebuilding fingerprints and proxies |
| **Local automation** | Local API inside an environment; CDP after launch for repricing, scraping, listing |

---

## Get started

| Step | Action |
|:---:|---|
| 1 | Download the client from [covebrowser.com](https://covebrowser.com/) (Windows / macOS) |
| 2 | Sign in with email (personal or team) |
| 3 | Create an environment (fingerprint, proxy, notes) |
| 4 | Launch; enable the local API when you need automation |

<div align="center">

<br/>

**Get started** ★ [Download Cove Browser](https://covebrowser.com/)

</div>

---

## Contact

| | |
|---|---|
| Website | [covebrowser.com](https://covebrowser.com/) |
| Email | [support@covebrowser.com](mailto:support@covebrowser.com) |
| Telegram | [@covebrowser](https://t.me/covebrowser) |
| Issues | [covebrowser-bit/CoveBrowser](https://github.com/covebrowser-bit/CoveBrowser/issues) |

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=covebrowser-bit/CoveBrowser&type=Date)](https://star-history.com/#covebrowser-bit/CoveBrowser&Date)

---

<div align="center">
<sub>MIT License ， Installers from the website</sub>
</div>
