<div align="center">
  <img src="https://raw.githubusercontent.com/sumitrawat2417/upi-flow-public/main/icon-512.png" width="90" height="90" alt="UPI Flow Logo" />
  <h1>UPI Flow</h1>
  <p><strong>A lightning-fast, offline-first Progressive Web App for smart UPI payment management.</strong></p>

  <p>
    <a href="https://sumitrawat2417.github.io/upi-flow-public/"><b>🚀 Launch Live App</b></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/PWA-Ready-E8435A?style=flat-square" alt="PWA Ready" />
    <img src="https://img.shields.io/badge/Offline--First-Yes-22C55E?style=flat-square" alt="Offline First" />
    <img src="https://img.shields.io/badge/No%20Backend-Local%20Only-1A1A2E?style=flat-square" alt="No Backend" />
    <img src="https://img.shields.io/badge/Made%20in-India-FF9933?style=flat-square" alt="Made in India" />
  </p>
</div>

---

> ⚠️ **Repository Notice**  
> **This is a public-facing repository used exclusively for deploying the compiled application.**  
> The source code and intellectual property for **UPI Flow** are maintained in a separate private repository. For inquiries regarding the source code or commercial licensing, please contact the author.

---

## 📖 What Is UPI Flow?

**UPI Flow** is a sleek, local-first merchant utility for managing UPI payments without any backend, account signup, or internet dependency after install.

Built in response to the UPI merchant pricing framework (September 2026), UPI Flow helps merchants split large payment totals into smaller sequential amounts — each with its own QR code — and guides them through a clean, counter-style confirmation workflow.

> UPI Flow is a **QR code generator and payment session manager**. It does not process, hold, or transfer any funds. All money flows directly through the merchant's normal UPI bank infrastructure.

---

## ✨ Features

### Core Workflow
- 🏪 **Merchant Onboarding** — Set up your business name and UPI ID in under 30 seconds. Scan an existing UPI QR to auto-fill your ID.
- ⚡ **Smart Split Engine** — Enter any amount. UPI Flow instantly calculates the optimal split (e.g., ₹5,500 → ₹2,000 + ₹2,000 + ₹1,500).
- 🎯 **Custom Split** — Override the auto split and enter your own amounts. The app validates they add up correctly.
- 📲 **Sequential Payment Sessions** — One QR at a time. Merchant taps "Mark Received" after confirming in their UPI app, and the next QR appears automatically.
- 📜 **Local History** — Every session is saved to the device. Review past sessions, see individual QR breakdowns, and delete when needed.

### UPI ID Management
- ➕ **Multiple UPI IDs** — Add, label, and manage multiple UPI IDs (e.g., GPay, PhonePe, Bank) under a single profile.
- 🔄 **Round-Robin Mode** — Optionally rotate QRs across all your UPI IDs automatically within a session.
- 📷 **QR Scan to Add** — Scan an existing UPI QR with the camera or upload an image to extract and add a UPI ID instantly.

### App Experience
- 🌗 **Theme Engine** — Light, Dark, or System (auto-follows device setting, updates in real-time).
- 📱 **Portrait-Only Design** — Optimized exclusively for mobile portrait use. Landscape mode shows a rotate prompt.
- 📲 **Install Banner** — Prompts the merchant to install to home screen on every fresh launch.
- ⚙️ **Configurable Threshold** — The ₹2,000 split threshold is adjustable in Settings. Future-proof against policy changes.

### Privacy & Data
- 🔒 **100% Local** — All data (profiles, sessions, history) stays on the device. No servers, no accounts, no cloud.
- 📊 **Export to CSV** — Export full payment history with session-level and individual QR-level breakdowns for accounting.
- 🗑️ **Clear & Reset** — Clear history or reset all data with proper confirmation safeguards (type "RESET" to confirm).

### Legal & Compliance
- 📄 **In-App Legal Pages** — Privacy Policy (DPDPA 2023-aligned), Terms of Use, and Help & FAQ all built into the app.

---

## 🛠️ Technology

| Layer | Technology |
|-------|-----------|
| UI Framework | React 19 + TypeScript |
| Build Tool | Vite 8 |
| Styling | Tailwind CSS v4 + CSS Custom Properties |
| QR Generation | qrcode.react |
| QR Scanning | qr-scanner |
| Local Storage | localStorage (via custom hook) |
| Routing | React Router DOM v7 (HashRouter) |
| Icons | Lucide React |
| Font | Outfit (Google Fonts) |

---

## 📱 How to Install

**Android (Chrome):**
1. Open the app link above
2. Tap the banner at the bottom, or use the browser's "Install App" menu
3. Tap "Add to Home Screen"

**iPhone (Safari):**
1. Open the app link in Safari
2. Tap the Share button → "Add to Home Screen"
3. Tap "Add"

Once installed, the app launches in full-screen portrait mode, just like a native app.

---

## 🔗 Links

- **Live App:** [https://sumitrawat2417.github.io/upi-flow-public/](https://sumitrawat2417.github.io/upi-flow-public/)
- **Organization:** [ManSula](https://mansula.netlify.app/) · [ManSula DivLabs](https://mansuladivlabs.netlify.app/)
- **Support:** sumitrawat2417@gmail.com

---

<div align="center">
  <p><em>Built by Forbit (Sumit Rawat) · A ManSula DivLabs product</em></p>
  <p><sub>Not affiliated with NPCI, any UPI operator, or bank.</sub></p>
</div>
