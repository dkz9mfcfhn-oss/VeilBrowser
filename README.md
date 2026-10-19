# 隐幕 / VeilBrowser

An iOS private browser with fixed Yandex (yandex.tm) search, nonpersistent website data, local native advertising filters and website video controls.

## Current distribution source — 1.0 build 12

[VeilBrowser-Native-1.0-build12-Source.zip](VeilBrowser-Native-1.0-build12-Source.zip) contains the complete standalone Xcode project and selected icon. Project-owned code is provided under MIT, with LICENSE inside this archive. Development Team is blank in this public source; no signing keys or user account data are included.

This version does not include or link AdGuard SafariConverterLib, FilterEngine, Scriptlets, ExtendedCss, imported filter lists, or a third-party rule updater. Advertising filters are independently authored native WebKit rules and local page-cleaning scripts. Their coverage is smaller than a full third-party filter engine. They cannot remove every advertisement. No VPN, proxy subscription, offline video downloader or analytics SDK is included.

Open VeilBrowser.xcodeproj with Xcode; iOS 17+, iPhone/iPad. Choose your own signing team. Native filter regression checks on iOS 27 simulator pass; real-site/media/device coverage is not implied. App Store review has not been submitted or approved.

[Privacy policy](PRIVACY.md) · [Support and privacy questions](https://github.com/dkz9mfcfhn-oss/VeilBrowser/issues). Do not post sensitive information publicly.

## Historical GPL distribution

VeilBrowser-OpenSource.zip is the earlier 1.3 build 6 GPL-3.0-only source snapshot containing third-party AdGuard components. Root LICENSE, COPYING, THIRD_PARTY.md and APPSTORE-PERMISSION-PENDING.md relate to that historical distribution. They are preserved with their original terms. No App Store exception has been obtained for those components; the current standalone distribution excludes them. The MIT grant covers project-owned material in the new archive only and does not relicense historical third-party code or filter contributions.

## Source integrity

Native source archive SHA-256: `c3856a22b181d0f347857409c7317b77b0f1d96f21e2c31e23b390901d68e4cc`
