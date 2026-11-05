<img src="docs/assets/update-shelf-icon-092.png" alt="Update Shelf app icon" width="128" height="128">

# Update Shelf Releases

## Current stable release

**Update Shelf 0.9.6 (build 121)** for Apple silicon Macs. Free download; Support development is optional.

[Download page](https://webservices-org.github.io/update-shelf-releases/) · [Release notes](https://github.com/WEBServices-ORG/update-shelf-releases/releases/tag/v0.9.6-build121)

New in 0.9.6: Clear numbered scan outcomes, completion timestamps including seconds, and VoiceOver scan-completion announcements without moving focus. Plug-in search tolerates surrounding whitespace and singular file/group labels are corrected. The manual read-only plug-in inventory covers AU, VST, VST3, CLAP and AAX in standard folders; latest plug-in versions are not checked and plug-ins are not installed.

Opening or reopening Update Shelf shows saved results without starting an update check. Manual checks and separately enabled scheduled checks remain available. Saved results cannot authorize installation until refreshed. Broader release QA remains partial.

The app and disk image are Developer ID signed, Apple-notarized and stapled. The in-app update feed offers build121.

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

[Download Update-Shelf-0.9.6-Apple-Silicon.dmg](https://github.com/WEBServices-ORG/update-shelf-releases/releases/download/v0.9.6-build121/Update-Shelf-0.9.6-Apple-Silicon.dmg), open it, and drag Update Shelf into Applications.

DMG SHA-256: `a78f06a7a7ef43872db0b5f65c56a0f5f5b98753241da8ca45190fae3109a53f`

The public release shelf retains 0.9.0, 0.9.1, 0.9.2, 0.9.3, 0.9.4, 0.9.5 and 0.9.6. Earlier releases and their downloadable assets were removed at the owner’s request; the primary download points to 0.9.6.
