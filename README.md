# B1 — Software Releases

<div align="center">

**🚀 Enterprise-Grade | 🔒 Secure | 🇮🇳 GST Compliant | 📱 Cross-Platform**

*Next-gen billing, accounting, and restaurant POS platform with end-to-end encryption, immutable audit trails, and India GST compliance.*

[![Latest Release](https://img.shields.io/github/v/release/el-kaid/b1-releases?label=latest&style=for-the-badge)](https://github.com/el-kaid/b1-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/el-kaid/b1-releases/total?style=for-the-badge)](https://github.com/el-kaid/b1-releases/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=for-the-badge)]()

</div>

---

## 📥 Download

Head to the [**Releases**](https://github.com/el-kaid/b1-releases/releases/latest) page and download the installer for your platform:

| Platform | File | Architecture |
|----------|------|--------------|
| **Windows** (Installer) | `B1-Setup-x.x.x.exe` | x64 |

> **Auto-Update:** B1 includes built-in auto-update support. Once installed, new versions will be downloaded and applied automatically.

---

## ✨ What is B1?

**B1** is a modern, secure billing and accounting desktop application built for **Indian businesses**. It combines professional-grade bookkeeping with cutting-edge automation.

### Key Features

- 📊 **Double-Entry Bookkeeping** — Chart of Accounts, Journal Entries, Trial Balance, P&L, Balance Sheet
- 🏪 **Inventory Management** — Real-time stock tracking, multi-warehouse, batch/serial tracking, low-stock alerts
- 📄 **GST-Compliant Invoicing** — E-Invoice (NIC), IRN generation, GSTR-1/3B reports, E-Way Bills
- 🍽️ **Restaurant POS** — Fast billing, KOT/KDS, QR ordering, bill splitting, smart upsells
- 💰 **Payments** — Razorpay integration, UPI, cards, payment links, SMS reminders via Twilio
- 👥 **CRM** — Customer & vendor management, credit limits, GSTIN validation
- 📈 **Reports & Analytics** — Sales, purchase, inventory, financial, and GST reports with PDF/Excel export
- 🔐 **Enterprise Security** — AES-256-GCM encryption, immutable hash-chain audit trail, OpenTimestamps, RBAC
- 🤖 **AI-Powered** — Predictive insights, smart upsell engine, OCR receipt scanning *(coming soon)*

---

## 🖥️ System Requirements

| Requirement | Minimum |
|-------------|---------|
| **OS** | Windows 10+, macOS 11+, Ubuntu 20.04+ |
| **RAM** | 4 GB |
| **Disk** | 500 MB free space |
| **Display** | 1280 × 720 |

---

## 🚀 Installation

### Windows
1. Download `B1-Setup-x.x.x.exe` from [Releases](https://github.com/el-kaid/b1-releases/releases/latest)
2. Run the installer — you can choose the installation directory
3. Launch **B1** from the Start Menu or Desktop shortcut

### macOS
1. Download `B1-x.x.x.dmg` from [Releases](https://github.com/el-kaid/b1-releases/releases/latest)
2. Open the DMG and drag **B1** to your Applications folder
3. On first launch, right-click → Open (to bypass Gatekeeper)

### Linux
1. Download `B1-x.x.x.AppImage` or `B1-x.x.x.deb` from [Releases](https://github.com/el-kaid/b1-releases/releases/latest)
2. **AppImage:** `chmod +x B1-*.AppImage && ./B1-*.AppImage`
3. **Debian:** `sudo dpkg -i B1-*.deb`

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| **Desktop** | Electron 38 + React 18 + TypeScript + Vite |
| **Backend** | NestJS 10 + Node.js |
| **Databases** | PostgreSQL 14+ (primary) · MongoDB 6+ (logs/audit) |
| **Styling** | TailwindCSS |
| **Security** | AES-256-GCM · RSA-4096 · OpenTimestamps · bcrypt · Helmet |
| **Infra** | Docker · Kubernetes · Terraform · GitHub Actions CI/CD |

---

## 🗺️ Roadmap

| Phase | Status |
|-------|--------|
| Core Bookkeeping (Double-entry, Chart of Accounts, Financial Reports) | ✅ Complete |
| Inventory & Invoicing (Stock, E-Invoice, GST Reports) | ✅ Complete |
| Restaurant POS (Billing, KOT/KDS, Upsell Engine) | ✅ Complete |
| Advanced Automation (OCR, ML categorization, AI bookkeeping) | 🔄 In Progress |
| Mobile App (Flutter, offline-first, camera receipt capture) | 📋 Planned |
| Enterprise Features (Multi-company, white-label, custom reports) | 📋 Planned |

---

## 🔐 Security

B1 takes security seriously:

- **End-to-End Encryption** — All sensitive financial data encrypted with AES-256-GCM
- **Immutable Audit Trail** — Hash-chain linked entries anchored to the Bitcoin blockchain via OpenTimestamps
- **Role-Based Access Control** — Granular permissions for every module
- **Zero-Knowledge Architecture** — The server never sees plaintext sensitive data
- **OWASP Top 10 Compliant** — Protection against all common web vulnerabilities

---

## 📞 Support

- 📧 **Email:** support@elkaid.com
- 🐛 **Bug Reports:** [Open an Issue](https://github.com/el-kaid/b1-releases/issues)
- 📖 **Documentation:** Included in-app and in the source repository

---

## 📄 License

**Proprietary** — All rights reserved. Unauthorized copying, modification, or distribution is strictly prohibited.

---

<div align="center">

**Made with ❤️ for Indian Businesses**

</div>
