<div align="center">
  <h1>UPI Flow</h1>
  <p><strong>A lightning-fast, offline-first Progressive Web App (PWA) for smart UPI payment management.</strong></p>
  
  <p>
    <a href="https://sumitrawat2417.github.io/upi-flow-public/"><b>Launch Live App</b></a>
  </p>
</div>

---

> ⚠️ **Repository Notice**  
> **This is a public-facing repository used exclusively for deploying the compiled application.**  
> The source code and intellectual property for **UPI Flow** are hosted in a separate, private repository and remain the exclusive property of the creator. For inquiries regarding the source code or commercial use, please contact the author directly.

---

## 📖 About The Project

**UPI Flow** is a sleek, local-first utility engineered to help merchants, shop owners, and freelancers handle large UPI payments effortlessly. 

Built in response to modern UPI transaction dynamics, UPI Flow solves a specific problem: managing large transaction totals by intelligently splitting them into smaller, manageable chunks. The app guides the merchant through a seamless, counter-style workflow to request and verify each split payment sequentially without any confusion.

### Why UPI Flow?
* **Zero MDR Navigation**: Helps merchants split large totals into chunks under ₹2,000 to navigate standard zero-MDR (Merchant Discount Rate) thresholds for P2M transactions.
* **No Banks, No Wallets, No KYC**: UPI Flow does not hold funds or act as a payment gateway. It simply generates intent-driven QR codes that route money directly to the merchant's existing bank account.

---

## ✨ Key Features

- 🧠 **Smart Split Engine**: Instantly takes a large total (e.g., ₹5,500) and calculates an optimal, configurable split (e.g., ₹2,000 + ₹2,000 + ₹1,500).
- 📲 **Sequential Payment Sessions**: Guides the merchant through a step-by-step counter workflow. Once one QR code is paid and verified, the next one automatically appears.
- ⚡ **Offline-First Architecture**: Designed for unreliable network conditions. Merchant profiles, sessions, and history are stored locally via IndexedDB. No backend servers required.
- 📱 **Native PWA Experience**: Installable directly to the device home screen for a seamless, full-screen native app feel on both Android and iOS.
- 🔒 **Total Privacy**: 100% of the merchant data stays on the device.

---

## 🛠️ Technology Highlights

While the source code is private, the application is built using a modern, high-performance web stack:
- **Frontend Framework**: React 19 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS v4
- **Data Persistence**: IndexedDB (via Dexie.js)
- **Validation**: Zod

---
<div align="center">
  <p><em>Designed and Developed by Sumit Rawat</em></p>
</div>
