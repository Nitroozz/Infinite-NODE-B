<h1 align="center">INFINITE [NODE-B]</h1>

<p align="center">
  <img width="599" height="114" alt="INFINITE Header" src="https://github.com/user-attachments/assets/3ea4a38a-b114-44b0-8ae6-38fa0663d31b" />
</p>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-supported-sites">Supported Sites</a> •
  <a href="#-setup--usage">Setup & Usage</a> •
  <a href="#-credits--acknowledgments">Credits</a>
</p>

---

## 📌 Overview

**INFINITE [NODE-B]** serves as a high-speed secondary node designed to complement Node A within the INFINITE proxy ecosystem.

This implementation leverages **Ultraviolet** by **Titanium Network**, utilizing service worker interceptors and Wisp WebSocket transport. Node B delivers robust client-side link rewriting and high-compatibility web proxying to ensure smooth streaming, dynamic assets, and unblocked browsing across restricted environments.

---

## 🌐 Supported Sites

Node B is optimized for high-traffic web applications, media streaming, and modern JS-heavy platforms:

- [YouTube](https://youtube.com)
- [Discord](https://discord.com)
- [Spotify](https://spotify.com)
- [Reddit](https://reddit.com)
- [Google](https://google.com)
- [X (Twitter)](https://twitter.com)
- [Instagram](https://instagram.com)
- [GeForce NOW](https://play.geforcenow.com/)

> **Note:** For maximum video streaming stability and minimal CAPTCHA challenges, run Node B on a clean residential or non-flagged hosting IP.

---

## 🛠️ Setup / Usage

Ensure you have **Node.js 18+** and **Git** installed on your server environment:

```bash
# Clone Node B Repository
git clone [https://github.com/Nitroozz/Infinite-NODE-B.git](https://github.com/Nitroozz/Infinite-NODE-B.git) node-b
cd node-b

# Install Dependencies
npm install

# Launch Server (Runs on Port 4000)
npm start
