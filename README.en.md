<div align="center">

<img src="docs/assets/logo.png" width="80" alt="Cove Browser" />

# Cove Browser

### Free fingerprint browser platform for cross-border e-commerce

One store, one environment ！ fingerprint ， cookies ， proxy egress  
Safer multi-store ops without account bleed

<br/>

[English](./README.en.md) ， [嶄猟](./README.md)

<br/>

<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/Free%20platform-22C55E?style=for-the-badge" alt="Free platform" /></a>
&nbsp;
<a href="https://covebrowser.com/"><img src="https://img.shields.io/badge/Download-Windows%20%7C%20macOS-0A7CFF?style=for-the-badge" alt="Download" /></a>
&nbsp;
<a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT" /></a>

<br/><br/>

**Free download** ★ [covebrowser.com](https://covebrowser.com/)　��　Current **v0.1.14**

</div>

<br/>

| Free to start | Store isolation | Team collaboration |
|:---:|:---:|:---:|
| Free client download ！ sign up and go | One store, one environment | Roles, assignment, shared workspace |

---

## Contents

- [Platform](#platform)
- [Detection results](#detection-results)
- [Use cases](#use-cases)
- [Get started](#get-started)
- [Contact](#contact)

---

## Platform

Cove Browser is a **free fingerprint browser platform** for cross-border sellers, agencies, and ops teams.  
For Amazon, Shopify, Shopee, TikTok Shop and more, each storefront becomes an isolated runtime ！ fingerprint, cookies, storage, and proxy egress stay separate ！ with account warm-up, window sync, and local automation to reduce store linking and team account bleed.

### Why we built a free platform

What sellers actually need is **store isolation, reliable browsers, and team collaboration**. Many commercial fingerprint browsers lock those basics behind expensive plans ！ billed by environments, seats, or windows. More stores and more teammates mean the bill scales up fast.

What that usually looks like:

| Reality | Cost |
|---|---|
| **Billed by environment / seat** | A few more stores or teammates and the monthly fee jumps |
| **Features gated by plan** | Window sync, team roles, and API often sit in paid tiers |
| **Tool cost outruns value** | Solo sellers and studios spend on the browser instead of ads and inventory |
| **Risk remains** | Paying more still doesn¨t remove store linking, cookie bleed, or proxy mismatch |

We built Cove Browser to make multi-account isolation a **free platform you can start with** ！ solve isolation and collaboration first, then put budget back into the business. Free client download from the website; sign up and go.

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

Teams worry about three things: **linked stores**, **shared browsers causing account bleed**, and **tool fees rising faster than margin**.  
Cove Browser turns every store or account into an isolated environment ！ and ships that isolation as a free platform for sellers, agencies, and studios.

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="Multi-store isolation" />
  &nbsp;&nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="Social matrix isolation" />
</p>

| Scenario | Pain point | How Cove helps |
|---|---|---|
| **Multi-marketplace ops** | Same-machine logins link stores; commercial tools charge per environment as you scale | One store, one environment + regional proxy; start on a free platform |
| **Registration & warm-up** | Unstable device / IP profiles fail review and warm-up | Keep fingerprint and egress IP consistent from signup through growth |
| **Ads & reporting** | Switching ad accounts wastes time; one shared browser risks bleed | Separate Meta / Google / on-platform accounts; window sync for budgets and reports |
| **Social & private-domain** | Cookie bleed links matrix accounts | Isolate Facebook, Instagram, TikTok, YouTube, WhatsApp |
| **Agencies & teams** | Seat fees stack; handoffs mean rebuilding fingerprints and proxies | Group by client 〜 store with roles; shared environment library |
| **Local automation** | Automation often sits behind another paid tier | Local API + CDP inside a chosen environment for repricing, scraping, listing |

---

## Get started

| Step | Action |
|:---:|---|
| 1 | **Free download** from [covebrowser.com](https://covebrowser.com/) (Windows / macOS) |
| 2 | Sign up / sign in with email |
| 3 | Create an environment (fingerprint, proxy, notes) |
| 4 | Launch; enable the local API when you need automation |

<div align="center">

<br/>

**Start free** ★ [Download Cove Browser](https://covebrowser.com/)

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
<sub>MIT License ， Free platform ， Installers from the website</sub>
</div>
