<div align="center">

<img src="docs/assets/logo.png" width="72" alt="Cove Browser" />

# Cove Browser

**Enterprise fingerprint browser ¡ª desktop client**

[English](./README.en.md) ¡¤ [ÖÐÎÄ](./README.md)

A desktop client for everyday users and teams: create environments, bind proxies, manage members, and sync windows ¡ª without hand-crafting CLI flags.

- Download: [covebrowser.com](https://covebrowser.com/) (Windows ¡¤ macOS)
- Current client: **Cove Browser v0.1.14**

</div>

---

## Contents

- [Website](#website)
- [Screenshots](#screenshots)
- [Features](#features)
- [Detection samples](#detection-samples)
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

## Screenshots

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

### Scenarios

Multi-store and social matrices with isolated cookies, fingerprints, and egress.

<p align="center">
  <img src="docs/assets/scenario-stores.webp" width="420" alt="Multi-store scenario" />
  &nbsp;
  <img src="docs/assets/scenario-social.webp" width="420" alt="Social scenario" />
</p>

---

## Features

| Feature | Notes |
|---|---|
| Multi-account environments | Isolated fingerprint, cookies, storage, proxy |
| Batch ops | Create, import, start, stop, recycle bin |
| Groups & tags | Organize by project / client / owner |
| Window sync | Mirror mouse, keyboard, and scroll |
| Local API | Localhost JSON API; returns CDP after launch |
| Team collaboration | Members, roles, permissions |
| Proxies | HTTP / HTTPS / SOCKS5 with connectivity checks |

Profiles present as **Chrome** (UA / Client Hints) on detection sites.

---

## Detection samples

<p align="center">
  <img src="docs/assets/detect-fingerprint.webp" width="720" alt="Fingerprint sample" />
</p>

<p align="center">
  <img src="docs/assets/detect-browserscan.png" width="720" alt="BrowserScan sample" />
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
