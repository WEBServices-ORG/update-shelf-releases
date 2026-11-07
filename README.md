<img src="docs/assets/update-shelf-icon-092.png" alt="Update Shelf app icon" width="128" height="128">

# Update Shelf Releases

## Current stable release

**Update Shelf 0.9.8 (build 128)** for Apple silicon Macs. Free download; Support development is optional.

[Download page](https://webservices-org.github.io/update-shelf-releases/) · [Release notes](https://github.com/WEBServices-ORG/update-shelf-releases/releases/tag/v0.9.8-build128)

New in 0.9.8: broader Mac App Store detection and Homebrew build comparisons; reviewed direct stable Sparkle ZIP updates with artifact/signature checks and retained app recovery; detection-only cask comparisons; explicit Sparkle preview selection; official TONE3000 release comparisons across installed plug-in formats. Other plug-ins remain inventory/vendor handoffs and are not installed.

Direct updates require a user-owned target and a supported single-app ZIP. DMG/PKG/delta, nested apps and framework-link archives remain external. Recovery keeps the app bundle, not documents or settings, and requires the recorded destination to remain present.

Opening or reopening Update Shelf shows saved results without starting an update check. Manual checks and separately enabled scheduled checks remain available. Saved results cannot authorize installation until refreshed. Broader release QA remains partial.

The app and disk image are Developer ID signed, Apple-notarized and stapled. The in-app update feed offers build128.

Source coverage varies. App Store updates remain managed by Apple; unsupported app updaters are handoffs, not direct installs. Broader keyboard/VoiceOver, second-Mac/standard-account, natural timer delivery across sleep, and failure/denial coverage remain unfinished. Stable designation does not claim those checks passed.

## What the app does

Update Shelf finds supported updates for Mac apps and tools, installs eligible updates after review, and directs you to the responsible app or store for the rest.

- **Check:** Homebrew apps and tools, global npm packages, uv tools, connected GitHub releases, and supported built-in app update sources. Coverage varies; unknown versions stay unknown.
- **Install:** eligible Homebrew, npm, uv and verified stable Sparkle ZIP updates through a reviewed, sequential queue. Direct app updates retain a recovery copy; failure stops the queue. App Store updates remain with Apple; unsupported vendor updates require their own updater or website.
- **Organize:** search, name/size sorting, postponement until tomorrow or next week, ignore-app and skip-version controls.
- **Review outcomes:** searchable, filterable history distinguishes verified changes, failures, and results needing another check. Check again does not install anything.
- **Connect sources:** supported GitHub release checks, identity-bound developer website bookmarks, detection-only cask comparisons and optional Sparkle preview checks. A bookmark alone does not provide automated version checks or installation authority.
- **Choose automation:** separately enabled scheduled checks and a separately enabled automatic tier limited to one eligible Homebrew app per successful cycle. Opening the app never starts an update check.

Not every Mac app or plug-in is covered. An update candidate is not necessarily installable here. Signing/notarization and targeted tests do not mean broader QA is complete.

## Install

[Download Update-Shelf-0.9.8-Apple-Silicon.dmg](https://github.com/WEBServices-ORG/update-shelf-releases/releases/download/v0.9.8-build128/Update-Shelf-0.9.8-Apple-Silicon.dmg), open it, and drag Update Shelf into Applications.

DMG SHA-256: `52d1158e3d37e6bb10b494069ebc5d7b76e9f01bac42c9a7788f4c37295890b2`

Earlier releases remain historical; the primary download points to0.9.8/build128. See STATE.md for verification status and remaining QA limits.
