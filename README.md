<div align="center">

<img src="assets/sprout-app-icon.png" alt="Sprout Official App Logo" width="132" />

# 🌱 Sprout

### **Track money in seconds. Grow habits for life.**
*Your voice-first, privacy-focused AI expense companion for Android — built to feel effortless, warm, and razor-sharp.*

<p>
  <a href="https://github.com/alok-devforge/sprout-releases/releases/download/v1.1.0/sprout-v1.1.0.apk">
    <img src="https://img.shields.io/badge/Download_APK-v1.1.0-7CB518?style=for-the-badge&logo=android&logoColor=white" alt="Download Sprout v1.1.0 APK" />
  </a>
  <a href="https://github.com/alok-devforge/sprout-releases/releases">
    <img src="https://img.shields.io/badge/All_Releases-Changelog-1E2A22?style=for-the-badge&logo=github&logoColor=white" alt="All Releases" />
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Android-7.0%2B_(API_24%2B)-30A46C?style=flat-square&logo=android&logoColor=white" alt="Android 7.0+" />
  <img src="https://img.shields.io/badge/Size-102.5_MB-5A8A0F?style=flat-square" alt="APK Size 102.5 MB" />
  <img src="https://img.shields.io/badge/AI_Buddy-Powered_by_Groq-7CB518?style=flat-square" alt="AI Powered by Groq" />
  <img src="https://img.shields.io/badge/Privacy-Zero_Ads_%C2%B7_Masked_Balances-0E1510?style=flat-square" alt="Privacy First" />
</p>

---

<table>
  <tr>
    <td width="110" align="center">
      <img src="assets/sprout-wave.png" alt="Sprout Mascot Waving" width="88" />
    </td>
    <td align="left">
      <strong>Meet Sprout — the money tracker you don't dread opening.</strong><br/>
      Say <em>"Paid ₹140 for evening chai and samosa via UPI"</em>, snap a crumpled receipt, or log in two taps. Sprout parses intent with Groq AI, watches your daily runway, tracks recurring bills &amp; tiffin plans, and keeps every rupee private until you tap to peek.
    </td>
  </tr>
</table>

</div>

---

## ✨ Why People Love Sprout

| | Feature | What It Does for You |
| :---: | :--- | :--- |
| 🎙️ | **Voice-First AI Buddy** | Talk naturally or chat — powered by **Groq** to classify merchants, categories, payment modes, and split notes automatically across Voice, Quick Add, OCR, and Edits. |
| 👁️ | **Privacy-First Balance Masking** | Income and Total Balance stay hidden (`•••••`) by default so shoulder-surfers see nothing. Reveal or hide everything in one tap. |
| 📊 | **Deep Insights & Daily Runway** | Know your **Safe-to-Spend**, net cashflow, spending rhythm, category hotspots, and live pace at a glance on Home & Insights. |
| 🍱 | **Mess, Tiffin & Subscriptions** | Dedicated tracking for daily tiffin deliveries, recurring bills, and monthly plans — synced right alongside your ledger. |
| 📸 | **Instant Receipt OCR** | Point at any bill or receipt — on-device **ML Kit OCR** reads totals & merchants and hands off cleanly to Groq for instant categorization. |
| 🔒 | **Biometric Lock & Cloud Sync** | Lock Sprout with fingerprint/face authentication, work seamlessly offline, and keep your data synced across devices — plus one-tap **in-app updates**. |

---

## 🚀 Latest Release — `v1.1.0`

<div align="center">

| Property | Details |
| :--- | :--- |
| **Version** | `1.1.0` (Build `2`) |
| **Package** | [`sprout-v1.1.0.apk`](https://github.com/alok-devforge/sprout-releases/releases/download/v1.1.0/sprout-v1.1.0.apk) |
| **File Size** | `102.5 MB` (`107,521,345 bytes`) — universal APK (`arm64-v8a`, `armeabi-v7a`, `x86_64`) |
| **Min Android** | Android 7.0 (Nougat · API 24) and above |
| **SHA-256** | `D61514FF9D858BAAFEB551CD342BCAEBD3F9D9A72EB81307961BAD53CF2F30D3` |

</div>

### 🆕 Highlights in `v1.1.0`

- **Default Balance Privacy**: Masked Total Balance & Income on the Home screen with an instant eye-toggle button.
- **Home Daily Pulse & Runway**: Real-time daily budget runway stats surfaced directly on your dashboard.
- **Revamped Insights Engine**: Fixed timeframe comparisons & theme contrast bugs, and added Cashflow and Spending Rhythm analytics.
- **Smarter Groq Categorization**: Buddy voice/chat, Quick Add, OCR receipts, and transaction edits now route through Groq AI for accurate intent and category detection.
- **Reliable In-App Updates (OTA)**: Fixed Android `FileProvider` install handoff with a smooth fallback browser download option.
- **Release Stability Fix**: Preserved Firebase & ML Kit component constructors under Android R8 shrinking so release builds launch cleanly on all devices.

---

## 📲 How to Install or Update

1. **Download** [`sprout-v1.1.0.apk`](https://github.com/alok-devforge/sprout-releases/releases/download/v1.1.0/sprout-v1.1.0.apk) directly on your Android phone.
2. **Allow installation** from your browser/Files app if Android prompts *"Install unknown apps"* (one-time permission).
3. **Tap Update / Install** — existing Sprout users upgrade **in place** without losing local settings or needing to uninstall.
4. From `v1.1.0` onward, check **More → Check for Updates** inside the app anytime to get future releases automatically!

<details>
<summary><strong>🔍 Curious why the release APK (~102 MB) is half the size of test/debug builds (~230 MB)?</strong></summary>

<br/>

- **Debug builds** bundle the Dart JIT compiler, unstripped `kernel_blob.bin`, and debugging symbols across multiple CPU architectures.
- **Release builds** compile fast **AOT native machine code** (`libapp.so`) and run Android **R8 code & resource shrinking** to strip unused debug overhead — making the app smaller, faster to launch, and smoother to scroll with zero features removed.

You can verify integrity anytime using the SHA-256 hash above:
```bash
# Linux / macOS
shasum -a 256 sprout-v1.1.0.apk

# Windows (PowerShell)
Get-FileHash sprout-v1.1.0.apk -Algorithm SHA256
```

</details>

---

<div align="center">

<img src="assets/sprout-proud.png" alt="Sprout Mascot Proud" width="84" />

### Built with care by Indie Makers

**[Alok Kumar](https://www.linkedin.com/in/alok-devforge/)** · Founder &nbsp;|&nbsp; **[Sabnur Samiha](https://www.linkedin.com/in/sabnur-samiha/)** · Co-Founder

*This repository hosts official compiled Android builds and release notes for **Sprout**.*

</div>
