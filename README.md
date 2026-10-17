# SwipeRight — Data & Releases

**Which card to swipe, for what.** SwipeRight is an Indian credit card reward optimizer for macOS and Android. Pick the card that pays the most on every purchase — it ranks every card in your wallet by actual ₹ value returned, handling caps, UPI restrictions, merchant-specific rates, Amazon Prime status, EMI exclusions, and more.

---

## ⬇️ Download

| Platform | Version | Link |
|---|---|---|
| macOS (Apple Silicon) | v1.4.14 | [SwipeRight-v1.4.14-mac.dmg](https://github.com/itsmeshibintmz/swiperight-data/releases/download/v1.4.14/SwipeRight-v1.4.14-mac.dmg) |
| Android (APK) | v1.4.14 | [SwipeRight-v1.4.14-android.apk](https://github.com/itsmeshibintmz/swiperight-data/releases/download/v1.4.14/SwipeRight-v1.4.14-android.apk) |
| iOS / Windows | Planned | — |

> **macOS:** Right-click → Open the first time (app is unsigned — bypasses Gatekeeper warning).  
> **Android:** Enable "Install from unknown sources" in Settings → Apps → Special permissions, then open the APK.

[All releases →](https://github.com/itsmeshibintmz/swiperight-data/releases)

---

## ✨ Features

- **Tracker** — Pick spend type + merchant, enter amount → every card in your wallet ranked by ₹ returned
- **My Cards** — Track statement/due dates, interest-free days, billing cycle per card
- **Library** — Browse 87 Indian credit cards, filter by bank/network/benefit, best cards per spend type
- **Glass UI** — Liquid glass floating nav bar, frosted-glass sheets; blur intensity adjustable in Settings
- **In-app updater** — Checks this repo's `version.json` on launch and notifies when a new version is available
- **87 cards · 22 issuers** — HDFC, Axis, ICICI, SBI, IDFC FIRST, YES Bank, HSBC, RBL, Amex, AU Small Finance, Standard Chartered, OneCard, Kiwi, Jupiter, Kotak, IndusInd, Bank of Baroda, Scapia, and more. Includes Paytm SBI co-branded, Google Pay Flex (SBI + Axis), Axis SuperMoney
- **No account, no backend** — everything stored locally; wallet backup/restore as plain JSON

---

## 📦 What's in this repo

This is the **public data + releases** repo for SwipeRight. The app source code is kept private.

| File | Purpose |
|---|---|
| `version.json` | Latest release info — app polls this on launch to check for updates |
| `cards.json` | Reserved for future remote card data updates (OTA rate/card changes without a new build) |

### `version.json` format

```json
{
  "version": "1.4.14",
  "tag": "v1.4.14",
  "name": "Release title",
  "notes": "What changed in this version",
  "mac_url": "https://github.com/itsmeshibintmz/swiperight-data/releases/download/vX.Y.Z/SwipeRight-vX.Y.Z-mac.dmg",
  "android_url": "https://github.com/itsmeshibintmz/swiperight-data/releases/download/vX.Y.Z/SwipeRight-vX.Y.Z-android.apk"
}
```

---

## 📋 Recent Releases

| Version | What's in it |
|---|---|
| **v1.4.14** | 5 new cards: Paytm SBI, Paytm SBI SELECT, Google Pay Flex (SBI + Axis, Oct 2026 rates), Axis SuperMoney — 87 total |
| **v1.4.13** | Nav bar pill with proper 36px side margins — guaranteed by placing padding directly on the pill |
| **v1.4.10** | Nav bar anchored to bottom; Android in-app installer fixed (system APK installer) |

[Full release history →](https://github.com/itsmeshibintmz/swiperight-data/releases)

---

*Personal project by [@itsmeshibintmz](https://github.com/itsmeshibintmz) · Indian credit card reward optimizer*
