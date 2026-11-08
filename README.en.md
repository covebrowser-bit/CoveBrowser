<div align="center">

<img src="docs/assets/logo.png" width="72" alt="Cove Browser" />

# Cove Browser

**Fingerprint browser desktop client for cross-border e-commerce**

[English](./README.en.md) ， [嶄猟](./README.md)

Built for cross-border sellers and ops teams: isolate multi-store and multi-marketplace accounts, bind proxies, and sync windows for bulk work ！ without hand-crafting CLI flags.

- Download: [covebrowser.com](https://covebrowser.com/) (Windows ， macOS)
- Current client: **Cove Browser v0.1.14**

</div>

---

## Contents

- [Website](#website)
- [Detection results](#detection-results)
- [Use cases](#use-cases)
- [Features](#features)
- [Screenshots](#screenshots)
- [Get started](#get-started)
- [About this repo](#about-this-repo)
- [Contact](#contact)
- [Star History](#star-history)

---

## Website

[covebrowser.com](https://covebrowser.com/) introduces isolated environments, fingerprint controls, proxies, window sync, and team collaboration, and hosts installers.

<p align="center">
  <img src="docs/assets/website-hero.png" width="900" alt="Cove Browser website and desktop preview" />
</p>

<p align="center"><em>Marketing site + environment manager preview</em></p>

---

## Detection results

Profiles present as **Chrome** (UA / Client Hints). Below are sample results from public third-party detectors ！ retest yourself for evidence, not marketing claims alone.

| Detector | Focus | Notes |
|---|---|---|
| Fingerprint.com / similar | Canvas, WebGL, Audio, hardware consistency | Stable, reproducible profile fingerprint |
| BrowserScan and similar | Browser identity, timezone, language, WebRTC | Scored as a normal Chrome profile, not an unknown browser |
| Platform risk checks | Login / device signals | Self-check before store opening with region-matched proxy |

<p align="center">
  <img src="docs/assets/detect-fingerprint.webp" width="720" alt="Fingerprint sample" />
</p>

<p align="center"><em>Fingerprint-style sample: device and browser signals</em></p>

<p align="center">
  <img src="docs/assets/detect-browserscan.png" width="720" alt="BrowserScan sample" />
</p>

<p align="center"><em>BrowserScan-style sample: Chrome identity presentation</em></p>

> Results vary by detector algorithms and local setup. Before go-live, retest with the target region proxy and the intended environment.

---

## Use cases

Cross-border sellers usually worry about two things: **stores getting linked**, and **teams sharing one browser so accounts bleed into each other**. Cove Browser turns every store or account into an isolated environment ！ fingerprint, cookies, storage, and proxy egress stay separate ！ from solo sellers to agency-scale ops.

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="Multi-store scenario" />
  &nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="Social scenario" />
</p>

### Multi-marketplace, multi-store ops

Amazon, Shopify, eBay, Shopee, Lazada, Walmart, TikTok Shop, and more often mean dozens or hundreds of storefronts. Bind each store to its own environment and regional proxy so backend work, listing edits, and order handling stay isolated ！ reducing the risk that one flagged account takes others down with it.

### Store registration and account warm-up

New stores need stable device and network profiles through signup, review, and early growth. Plan environments for registration, login, and daily browsing so each account keeps a consistent fingerprint and egress IP over time ！ better for batch store opening and long-term maintenance.

### Ads and reporting consoles

Teams often run many ad accounts (Meta, Google, on-platform ads). Open each console in its own environment; window sync helps apply the same actions across accounts ！ budgets, reports, campaign toggles ！ without constant account switching and cache clearing.

### Social and private-domain matrices

Acquisition still leans on Facebook, Instagram, TikTok, YouTube, WhatsApp, and email tools. Isolate each account so publishing, DMs, and community ops can run in parallel without cookie bleed and account association.

### Agencies and studio collaboration

When you serve multiple clients, group environments by client 〜 store and assign what each teammate can see and do. Keep one shared environment library so handoffs do not mean rebuilding fingerprints and proxies from scratch.

### Local automation and batch jobs

For scripted repricing, scraping, or listing workflows, enable the local API inside a chosen environment. After launch you get a CDP endpoint ！ isolated profiles and efficiency tooling on one path.

---

## Features

Isolation verified by detectors, applied to daily store ops and team work:

| Feature | Notes |
|---|---|
| Multi-account environments | Isolated fingerprint, cookies, storage, proxy |
| Batch ops | Create, import, start, stop, recycle bin |
| Groups & tags | Organize by project / client / owner |
| Window sync | Mirror mouse, keyboard, and scroll |
| Local API | Localhost JSON API; returns CDP after launch |
| Team collaboration | Members, roles, permissions |
| Proxies | HTTP / HTTPS / SOCKS5 with connectivity checks |

---

## Screenshots

Desktop client UI (v0.1.x).

### Environment manager

Independent profiles for fingerprint, proxy, groups, and notes.

<p align="center">
  <img src="docs/assets/profiles.png" width="900" alt="Cove Browser environments" />
</p>

### Fingerprint settings

Configure Canvas / WebGL / Audio / hardware and OS parameters per profile.

<p align="center">
  <img src="docs/assets/fingerprint.png" width="900" alt="Cove Browser fingerprint settings" />
</p>

### Launch progress

Startup progress while the kernel and proxy become ready.

<p align="center">
  <img src="docs/assets/launch.png" width="720" alt="Cove Browser launch progress" />
</p>

---

## Get started

1. Download from [covebrowser.com](https://covebrowser.com/)  
2. Sign in with email  
3. Create an environment  
4. Launch; enable the local API when you need automation  

---

## About this repo

| | This repository |
|---|---|
| Includes | README, license, feature docs & screenshots |
| Does not include | Electron source, Chromium fingerprint kernel, backend, secrets |
| Installers | Distributed from the website, not as source in this repo |

---

## Contact

- Website: [covebrowser.com](https://covebrowser.com/)
- Email: [support@covebrowser.com](mailto:support@covebrowser.com)
- Telegram: [@covebrowser](https://t.me/covebrowser)
- Issues: [covebrowser-bit/CoveBrowser](https://github.com/covebrowser-bit/CoveBrowser/issues)

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=covebrowser-bit/CoveBrowser&type=Date)](https://star-history.com/#covebrowser-bit/CoveBrowser&Date)
