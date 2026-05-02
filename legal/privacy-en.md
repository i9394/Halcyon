---
title: "Privacy Policy"
layout: default
---

# Privacy Policy

**Effective Date:** 2026-04-18
**Last Updated:** 2026-05-02

Zeroneo Studio ("we", "us", or "our") operates the **Viohold** mobile application (the "App"). This Privacy Policy explains how we handle information when you use the App.

## Summary

- **We do not collect any personally identifiable information.**
- All browsing history, bookmarks, downloaded files, and settings stay on your device.
- If the App crashes, an anonymous crash report is automatically sent to help us improve stability — you can turn this off in Settings.
- The App does not contain third-party analytics, tracking SDKs, or advertising networks.

## Information Stored Locally on Your Device

The following data is stored **only on your device** and never transmitted to us or any third party:

| Data | Purpose | Storage |
|---|---|---|
| Browsing history | In-app history view | SwiftData (local SQLite) |
| Bookmarks | User bookmarks | SwiftData (local) |
| Open tabs | Tab session persistence | Local JSON |
| Downloaded files | File management | App sandbox |
| Cookies | Web browsing session | WKWebView managed, sandboxed |
| App settings | User preferences | iOS UserDefaults |
| Passcode / biometric | App lock | iOS Keychain + Face ID authentication |

You can delete all locally stored data at any time via the App's **Settings → Clear Cache** and **History → Clear All**, or by uninstalling the App.

## Permissions

The App requests the following iOS permissions, all used **only on your device**:

| Permission | Purpose | Required? |
|---|---|---|
| Camera | Scanning QR codes to open URLs (the camera output is processed locally, not uploaded) | Optional |
| Face ID / Touch ID | Unlocking the App when App Lock is enabled | Optional |
| Photos (save only) | Saving downloaded images to Photos when user explicitly requests | Optional |

Denying any permission does not restrict other App functionality.

## Diagnostics and Crash Information

### 1. When We Collect
When the App terminates unexpectedly (a crash), iOS generates a diagnostic report. The report is first stored locally on your device, then automatically sent to the developer on the App's next launch to help diagnose issues and improve stability.

### 2. What We Collect
We collect only de-identified technical information needed for crash triage:
- App version and build number
- Operating system version
- Device model (e.g. iPhone15,3)
- Time of crash

### 3. What We Do NOT Collect Through This Channel
- Browsing history, URLs, or search queries
- Downloaded files, playback history, or saved content
- Account information, email, or phone number
- Device identifiers (e.g. IDFA, IDFV)
- Location, contacts, photos, or any other privacy-sensitive permission data

### 4. Purpose
Collected information is used solely to investigate crashes and improve App stability. It is never used for advertising, user profiling, or any commercial analytics.

### 5. Storage and Sharing
Diagnostic information is sent to the developer's own feedback channel and used internally by the development team. It is never shared with or sold to any third party. Full system crash logs (MetricKit Diagnostic Payload) remain only on your local device under `Documents/metrics/` and are auto-deleted after 7 days.

### 6. Your Control
You can disable "Send crash diagnostics automatically" at any time via **Settings → Privacy & Security → Diagnostics**. Once disabled, the App will not send any diagnostic information.

## Third-Party Content and Services

- **Web pages you visit**: The App is a web browser. Any website you visit may collect information about you according to its own privacy policy — we have no control over third-party websites.
- **Ad-blocking rule lists**: The App periodically downloads public rule lists (Peter Lowe's list, EasyList China) from `pgl.yoyo.org` and `easylist-downloads.adblockplus.org` to update ad filters. These are **one-way downloads of public rule files**; no user data is sent.
- **Safari Content Blocker Extension**: Rule lists are shared with the system Safari browser via an iOS App Group container (`group.com.cnkira.viohold`). Data stays on your device.

## Data We Do NOT Collect

- Your personal information (name, email, phone number, address).
- Your location (the App does not request location permission).
- Your device identifier (IDFA / IDFV).
- Your browsing activity, search queries, or tab contents.
- Any tracking data or advertising analytics.

> Note: After a crash, the App sends a de-identified diagnostic report (see the "Diagnostics and Crash Information" section); this can be disabled in Settings.

## Children's Privacy

The App is rated **17+** (App Store age rating) due to unrestricted web access. We do not knowingly collect any data from users under 17.

## Copyright and Media Downloading

The App allows saving web page resources for offline access, similar to common web browser features such as Safari's "Add to Reading List" or built-in download managers. Users are responsible for respecting copyright law when saving content.

We maintain a **domain blocklist** that prevents media detection on major platforms (YouTube, Netflix, TikTok, Instagram, Facebook, Twitter, Bilibili, iQiyi, Spotify, Apple Music, and others). See `dmca-en.md` for the copyright infringement notification process.

## Changes to This Policy

We may update this Privacy Policy from time to time. The "Last Updated" date will reflect the latest revision. Continued use of the App after changes means acceptance of the updated policy.

## Contact

For privacy questions or data deletion requests:

**Email:** kirakingdx@hotmail.com

---

*This Privacy Policy applies only to the Viohold mobile application. It does not apply to third-party websites you visit through the App.*
