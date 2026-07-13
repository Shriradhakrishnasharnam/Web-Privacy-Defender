# Web Privacy Defender
Web Privacy Defender is a lightweight tool that protects your online identity by preventing WebRTC leaks, which can expose your real IP address, even when using a VPN. This extension ensures your IP remains hidden, adding an extra layer of privacy.
<div align="center">

# Web Privacy Defender

### A Modern Firefox Extension for Real-Time Privacy Protection

[![Firefox Add-on](https://img.shields.io/badge/Firefox-Add--on-FF7139?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://addons.mozilla.org/en-US/firefox/addon/web-privacy-defender/)
[![License](https://img.shields.io/badge/License-MIT-00C2A8?style=for-the-badge)](#license)
[![Version](https://img.shields.io/badge/Version-1.0.0-6C5CE7?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Active%20Development-0984E3?style=for-the-badge)](#)

**Block trackers. Stop fingerprinting. Take back your privacy — one tab at a time.**

[Features](#features) • [Installation](#installation) • [Usage](#usage) • [Roadmap](#roadmap) • [Contributing](#contributing) • [License](#license)

</div>

---

## Overview

**Web Privacy Defender** is a lightweight, open-source Firefox extension built to give users clear visibility and control over their online privacy. It identifies and blocks trackers, cookies, and fingerprinting attempts in real time, without slowing down your browsing experience.

Built with a focus on transparency, the extension shows exactly what is being blocked and why — so privacy protection is never a black box.

---

## Features

<table>
<tr>
<td width="50%" valign="top">

### Tracker Blocking
Detects and blocks known trackers, analytics scripts, and third-party cookies across every site you visit.

### Real-Time Dashboard
A live popup dashboard shows blocked trackers per tab and cumulative totals across all browsing sessions.

</td>
<td width="50%" valign="top">

### Fingerprinting Protection
Mitigates canvas and WebGL fingerprinting techniques used to silently identify and track users.

### WebRTC Leak Protection
Prevents WebRTC from exposing your local or public IP address to third-party sites.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Custom Allow/Block Lists
Full control to whitelist trusted domains or blacklist specific ones based on your preferences.

</td>
<td width="50%" valign="top">

### Privacy Score
Every site you visit is rated on a simple scale based on trackers detected, HTTPS usage, and permission requests.

</td>
</tr>
</table>

---

## Installation

### From Firefox Add-ons Store

Install directly from the official Firefox Add-ons store:
 
[![Get the Add-on](https://img.shields.io/badge/Get%20the%20Add--on-Firefox%20Store-FF7139?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://addons.mozilla.org/en-US/firefox/addon/web-privacy-defender/)
 
**Direct link:** [addons.mozilla.org/en-US/firefox/addon/web-privacy-defender](https://addons.mozilla.org/en-US/firefox/addon/web-privacy-defender/)


### Manual Installation (Development Build)

1. Clone this repository
   ```bash
   git clone https://github.com/Shriradhakrishnasharnam/web-privacy-defender.git
   ```
2. Open Firefox and navigate to:
   ```
   about:debugging#/runtime/this-firefox
   ```
3. Click **Load Temporary Add-on**
4. Select the `manifest.json` file from the cloned repository

---

## Usage

Once installed, the Web Privacy Defender icon appears in your toolbar.

| Action | Result |
|---|---|
| Click the toolbar icon | Opens the live dashboard for the current tab |
| Toggle site protection | Pause or resume blocking for the active site |
| Open Settings | Manage allow/block lists and blocking preferences |
| View Privacy Score | See a real-time rating for the site you are on |

---

## Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebExtensions API](https://img.shields.io/badge/WebExtensions%20API-FF7139?style=flat-square&logo=firefoxbrowser&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-6C5CE7?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

</div>

---

## Roadmap

- [ ] Real-time tracker blocking dashboard
- [ ] Canvas and WebGL fingerprinting protection
- [ ] WebRTC leak protection
- [ ] Automatic cookie cleanup on tab close
- [ ] Per-site privacy scoring system
- [ ] Custom allow/block list manager
- [ ] HTTPS-only enforcement mode
- [ ] Referrer header stripping and control

See the [open issues](https://github.com/Shriradhakrishnasharnam/web-privacy-defender/issues) for a full list of proposed features and known issues.

---

## Contributing

Contributions are what make open-source projects thrive. Any contributions are greatly appreciated.

1. Fork the repository
2. Create your feature branch
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes
   ```bash
   git commit -m "Add AmazingFeature"
   ```
4. Push to the branch
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

Please make sure to update tests and documentation as appropriate.

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">

**Built and maintained by Shriradhakrishnasharnam**

If this project helps you browse more safely, consider giving it a star.

</div>
