# Update Shelf Releases

## Current stable release

**Update Shelf 0.9.1 (build 115)** for Apple silicon Macs. Free download; Support development is optional.

[Download page](https://webservices-org.github.io/update-shelf-releases/) · [Release notes](https://github.com/WEBServices-ORG/update-shelf-releases/releases/tag/v0.9.1)

New in 0.9.1: a polished About window with the blue shelf icon, actual version/build, a concise description, WEBServices attribution, and links to the website, release notes, and problem reporting. About follows the app’s sleep/menu-bar behavior.

Opening or reopening Update Shelf shows saved results without starting an update check. Manual checks and separately enabled scheduled checks remain available. Saved results cannot authorize installation until refreshed. Broader release QA remains partial.

The app and disk image are Developer ID signed, Apple-notarized and stapled. The in-app update feed offers build115.

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

[Download Update-Shelf-0.9.1-Apple-Silicon.dmg](https://github.com/WEBServices-ORG/update-shelf-releases/releases/download/v0.9.1/Update-Shelf-0.9.1-Apple-Silicon.dmg), open it, and drag Update Shelf into Applications.

DMG SHA-256: `1d8bc9bd234fbb9fec601bc996f6ad82943401d65e0355b851aa01c8ef3f6f44`

The public release shelf retains 0.9.0 and 0.9.1. Earlier releases and their downloadable assets were removed at the owner’s request; the primary download points to 0.9.1.
