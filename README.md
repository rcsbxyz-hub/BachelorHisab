# BachelorHisab (ব্যাচেলর হিসাব) — Official Releases

**BachelorHisab** is a bilingual (বাংলা + English), 100% offline Android app built for students living in shared bachelor messes in Bangladesh — tracking personal expenses & income, mess meal rates & utilities, lend/borrow balances, and monthly budgets.

## Download

Download the latest APK from the **[Releases](https://github.com/rcsbxyz-hub/BachelorHisab/releases/latest)** page.

## Privacy

- All financial data is stored locally on your device.
- No account or cloud login is required.
- The app only checks `app-update.json` in this repository to notify you when a newer version is available.

---

### Release Maintainer Guide

This public repository contains **only** release metadata (`app-update.json`) and compiled APK downloads in GitHub Releases (application source code is kept in a separate private repository).

To publish a new app update:
1. Build and sign the new release APK with incremented `versionCode` and `versionName`.
2. Create a new GitHub Release in this repository (e.g., tag `v1.1.0`) and attach the APK.
3. Update `app-update.json` in `main` with the matching `latestVersionCode`, `latestVersionName`, `notes`, and `url` (either `https://github.com/rcsbxyz-hub/BachelorHisab/releases/latest` or the direct APK download URL).
