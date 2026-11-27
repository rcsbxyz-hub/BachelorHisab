<p align="center">
  <img src="assets/logo.svg" alt="BachelorHisab Logo" width="88" height="88" />
</p>

<h1 align="center">BachelorHisab (ব্যাচেলর হিসাব)</h1>

<p align="center">
  <strong>বাংলাদেশের ব্যাচেলর মেস ও শিক্ষার্থীদের জন্য ১০০% অফলাইন খরচ, মিল, দেনা-পাওনা ও বাজেট ট্র্যাকার।</strong><br/>
  A bilingual (বাংলা + English), 100% offline personal finance, mess meal, lend/borrow, and monthly budget Android app.
</p>

<p align="center">
  <a href="https://github.com/rcsbxyz-hub/BachelorHisab/releases/latest">
    <img src="https://img.shields.io/github/v/release/rcsbxyz-hub/BachelorHisab?color=047857&label=Latest%20Version&style=for-the-badge" alt="Latest Release" />
  </a>
  <a href="https://rcsbxyz-hub.github.io/BachelorHisab/">
    <img src="https://img.shields.io/badge/Official%20Website-Live-065F46?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Official Website" />
  </a>
  <img src="https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android 7.0+" />
  <img src="https://img.shields.io/badge/100%25%20Offline-Private-F59E0B?style=for-the-badge" alt="100% Offline" />
</p>

<p align="center">
  <a href="https://github.com/rcsbxyz-hub/BachelorHisab/releases/latest/download/BachelorHisab-v2.1.0.apk"><strong>⬇️ Download Latest APK (v2.1.0)</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://rcsbxyz-hub.github.io/BachelorHisab/"><strong>🌐 Official Website</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://rcsbxyz-hub.github.io/BachelorHisab/privacy-policy.html"><strong>🔒 Privacy Policy</strong></a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/rcsbxyz-hub/BachelorHisab/releases"><strong>📋 All Releases</strong></a>
</p>

---

## ✨ Key Features

- **⚡ Quick Add & Edit:** Amount-first numeric keypad sheet with one-tap categories, payment methods (`Cash`, `bKash`, `Nagad`, `Bank / Card`), full entry editing, and Undo-on-delete.
- **📅 Monthly Scoping:** Track balances, income, expenses, and budget progress per calendar month with an instant month switcher (`< Month Year >`) and all-time transaction history.
- **🍛 Mess & Meal Manager:** Track roommates' deposits, meal counts, shared bazar logs, automatic meal rates, and utility splits.
- **🤝 Lend & Borrow Ledger:** Keep track of receivables and payables between friends with one-tap settle toggles.
- **📊 Budget & Analytics:** Visual 270° budget ring, over-budget alerts, category breakdown bars, and payment-method summaries.
- **🇧🇩 Bilingual & Adaptive Theme:** Instant one-tap switch between **বাংলা** and **English** (rendered cleanly with **Hind Siliguri**), plus **Light**, **Dark**, and **System** themes.
- **💾 Safe Backup & Restore:** Full SQLite snapshot export and staged restore — your financial records never leave your phone.
- **🔔 Automatic Update Alerts:** Checks [`app-update.json`](app-update.json) automatically so you always know when a newer version is ready on the official website.

---

## 📱 App Preview

<table>
  <tr>
    <td align="center"><img src="assets/phone-home.png" alt="Home Screen" width="210" /><br/><sub><b>হোম (Home)</b></sub></td>
    <td align="center"><img src="assets/phone-transactions.png" alt="Transactions Screen" width="210" /><br/><sub><b>লেনদেন (Transactions)</b></sub></td>
    <td align="center"><img src="assets/phone-mess.png" alt="Mess Screen" width="210" /><br/><sub><b>মেস ও দেনা-পাওনা (Mess)</b></sub></td>
    <td align="center"><img src="assets/phone-budget.png" alt="Budget Screen" width="210" /><br/><sub><b>বাজেট (Budget)</b></sub></td>
  </tr>
</table>

---

## 🔒 Privacy & Security

- **100% offline:** Zero cloud accounts, zero ads, zero tracking.
- **On-device storage:** All financial entries stay locally on your Android device.
- Read the full bilingual privacy policy here: **[Privacy Policy](https://rcsbxyz-hub.github.io/BachelorHisab/privacy-policy.html)**.

---

<details>
<summary><strong>🛠️ Maintainer Release Workflow (Click to expand)</strong></summary>

This public repository hosts only the official static website, `app-update.json`, privacy policy, and signed APK releases (application source code is maintained privately).

To publish a new version (e.g. `v1.2.0` / `versionCode = 3`):
1. Build and sign `BachelorHisab-v1.2.0.apk` with the release keystore.
2. Add `releases/BachelorHisab-v1.2.0.apk` and update `app-update.json` (`latestVersionCode`, `latestVersionName`, `apkUrl`, `notes`) on `main`.
3. Push `main` and push tag `v1.2.0`:
   - **GitHub Actions (`sync-pages.yml`)** automatically updates `https://rcsbxyz-hub.github.io/BachelorHisab/`.
   - **GitHub Actions (`publish-release.yml`)** automatically publishes the GitHub Release and attaches the signed APK.
   - Installed apps automatically notify users and direct them to the official website download section.

</details>

---

<p align="center">
  © 2026 <strong>Rudro Chandro Sarker (RCS)</strong> · All Rights Reserved (<a href="LICENSE">License</a>) · <a href="mailto:rcsbxyz@gmail.com">rcsbxyz@gmail.com</a>
</p>
