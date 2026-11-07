<img src="docs/assets/update-shelf-icon-092.png" alt="Update Shelf app icon" width="128" height="128">

# Update Shelf Releases

## Current stable release

**Update Shelf 0.9.12 (build 146)** for Apple silicon Macs. Free download; Support development is optional.

[Download page](https://webservices-org.github.io/update-shelf-releases/) · [Release notes](https://github.com/WEBServices-ORG/update-shelf-releases/releases/tag/v0.9.12-build146)

New in 0.9.12: the details panel stays open, and you can resize it by dragging its divider. Re-scan all checks the current filtered list without installing anything. Plug-ins now lives under Update tools. App Store rows retain their adjacent Re-scan and app-specific Open App Store buttons. You can also check supported audio plug-ins, open their vendor updater after review, and verify the installed files afterward. Custom folders, exclusions and file details help you understand what is installed. Coverage varies by product; plug-in installation stays with the vendor.

Direct updates require a user-owned target and a supported single-app ZIP. DMG/PKG/delta, nested apps and framework-link archives remain external. Recovery keeps the app bundle, not documents or settings, and requires the recorded destination to remain present.

Opening or reopening Update Shelf shows saved results without starting an update check. Manual checks and separately enabled scheduled checks remain available. Saved results cannot authorize installation until refreshed. Broader release QA remains partial.

The app and disk image are Developer ID signed, Apple-notarized and stapled. The in-app update feed offers build146.

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

[Download Update-Shelf-0.9.12-Apple-Silicon.dmg](https://github.com/WEBServices-ORG/update-shelf-releases/releases/download/v0.9.12-build146/Update-Shelf-0.9.12-Apple-Silicon.dmg), open it, and drag Update Shelf into Applications.

DMG SHA-256: `1d976b8f37332ae80a82de6dc17e5d79d0661c546b72edeb66e3d40f26d68cd5`

Earlier releases remain historical; the primary download points to0.9.12/build146. See STATE.md for verification status and remaining QA limits.
