<img src="docs/assets/update-shelf-icon-092.png" alt="Update Shelf app icon" width="128" height="128">

# Update Shelf Releases

## Current stable release

**Update Shelf 0.9.3 (build 117)** for Apple silicon Macs. Free download; Support development is optional.

[Download page](https://webservices-org.github.io/update-shelf-releases/) · [Release notes](https://github.com/WEBServices-ORG/update-shelf-releases/releases/tag/v0.9.3-build117)

New in 0.9.3: Skipped Electron channels now remain not checked instead of being recorded as successful. Completed Sparkle and Electron feed reads are visible in Source status. Background notices and the menu distinguish known checking limitations from request failures. No expanded installation permissions; broader QA remains partial.

Opening or reopening Update Shelf shows saved results without starting an update check. Manual checks and separately enabled scheduled checks remain available. Saved results cannot authorize installation until refreshed. Broader release QA remains partial.

The app and disk image are Developer ID signed, Apple-notarized and stapled. The in-app update feed offers build117.

Source coverage varies. App Store updates remain managed by Apple; unsupported app updaters are handoffs, not direct installs. Broader keyboard/VoiceOver, second-Mac/standard-account, natural timer delivery across sleep, and failure/denial coverage remain unfinished. Stable designation does not claim those checks passed.

## What the app does

Update Shelf finds supported updates for Mac apps and tools, installs eligible updates after review, and directs you to the responsible app or store for the rest.

- **Check:** Homebrew apps and tools, global npm packages, uv tools, connected GitHub releases, and supported built-in app update sources. Coverage varies; unknown versions stay unknown.
- **Install:** eligible Homebrew, npm, and uv updates through a reviewed, sequential queue. App Store updates remain with Apple; unsupported vendor updates require their own updater or website.
- **Organize:** search, name/size sorting, postponement until tomorrow or next week, ignore-app and skip-version controls.
- **Review outcomes:** searchable, filterable history distinguishes verified changes, failures, and results needing another check. Check again does not install anything.
- **Connect sources:** supported GitHub release checks and identity-bound developer website bookmarks. A bookmark alone does not provide automated version checks or installation authority.
- **Choose automation:** separately enabled scheduled checks and a separately enabled automatic tier limited to one eligible Homebrew app per successful cycle. Opening the app never starts an update check.

Not every Mac app or plug-in is covered. An update candidate is not necessarily installable here. Signing/notarization and targeted tests do not mean broader QA is complete.

## Install

[Download Update-Shelf-0.9.3-Apple-Silicon.dmg](https://github.com/WEBServices-ORG/update-shelf-releases/releases/download/v0.9.3-build117/Update-Shelf-0.9.3-Apple-Silicon.dmg), open it, and drag Update Shelf into Applications.

DMG SHA-256: `d1f1c0ff5fcbe496f340426de8e1a70086f9b491d48c521cb6a16f4b38b1e1d5`

The public release shelf retains 0.9.0, 0.9.1, 0.9.2 and 0.9.3. Earlier releases and their downloadable assets were removed at the owner’s request; the primary download points to 0.9.3.
