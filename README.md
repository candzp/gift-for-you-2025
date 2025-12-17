# 🎁 Gift For You 2025

A simple, secure, and festive way to share digital gift card codes using QR codes — without exposing the actual codes publicly.

This project is designed for **personal gifting** (holidays, celebrations, thank-yous) and uses:
- a **public static viewer page** (GitHub Pages)
- a **private, offline generator** (not hosted)

---

## ✨ How It Works (High Level)

1. Each gift card code is **encrypted locally**.
2. A **secure URL** is generated and turned into a QR code.
3. The recipient scans the QR and lands on a festive web page.
4. They enter a **PIN** to unlock and copy their gift code.
5. The code is redeemed inside the **Lazada mobile app**.

🔐 The actual gift codes are **never stored or exposed publicly**.

---

## 📁 Project Structure

```text
/
├─ index.html        # Public viewer page (hosted via GitHub Pages)
├─ README.md         # This file
└─ (generator.html)  # Offline-only tool
