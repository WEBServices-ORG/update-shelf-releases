# Website description audit — 2026-11-08

Status: COMPLETE for source/documentation comparison; not a new end-to-end application acceptance run. Public copy unchanged.

## Baseline

- Live HTML downloaded with a cache-busting query and compared to the publication checkout: cmp exit0.
- Website baseline5d8843160d28b4aca2cd0c520914441a15738557.
- Installed /Applications/Update Shelf.app metadata independently reads0.9.14/build152.
- Matching v0914 source checkout1284633; git diff v0.9.14-build152 HEAD -- sources returned no changes. Release source/tag3e461af1c0a85b79313235da5d755c8a191cfdff.
- Reviewed current source, release/native verification records, and the owner's supplied app screenshot. No scans, installations, preference changes or fresh broad UI tests performed.

## Findings and suggested copy

1. **Plug-in handoff wording is too narrow.** The Check audio plug-ins card says to open the vendor manager. PluginManagerRoute.swift:15-30 resolves Melda and iZotope managers only when identity validation passes, otherwise an official page; BIAS X and TONE3000 use pages. Suggested: “Review the update, open the vendor manager or official download/release page, then verify the installed files when you return.” Use equivalent wording in the lead and release summary.
2. **Clarify compatibility limits.** “Unknown compatibility is shown clearly” is technically consistent but vague. PluginInventoryView.swift:356-358 always supplies an empty compatibility map and explicitly says OS/DAW compatibility is unknown. Suggested: “Inspect processor architecture and mixed versions across formats. Architecture detection does not establish macOS or DAW compatibility.”
3. **Separate history from library rechecking.** Re-scan all is in the main library toolbar (UpdateShelfApp.swift:872), not the history sheet (UpdateHistoryControls.swift). The current combined card can suggest otherwise. Suggested: “Search and filter recorded update outcomes. In the main library, Re-scan all rechecks the current filtered list without installing anything.”
4. **Add the minimum OS near Download.** Package.swift declares macOS14 and build-app.sh writes LSMinimumSystemVersion14.0. Suggested download requirement: “macOS 14 or later · Apple silicon.” Current Apple-silicon wording is accurate but incomplete.

## Claim reconciliation

| Website claim | Result / evidence |
|---|---|
| Apps/tools, sources, search, name/app-size sorting | Supported by library/source and LibrarySort implementations; size wording correctly limits this to app bundles |
| Automatic header/footer heights; adjustable side dividers; single scrolling action row | Supported by UpdateShelfApp.swift and header-rescan-2026-11-07.md native build152 evidence |
| Reviewed Homebrew/npm/uv and eligible signed Sparkle ZIP installs | Supported by BatchUpdateControls/DirectUpdateControls; serial queue and narrow direct-update restrictions are disclosed |
| Previous direct-update app bundle retained | Supported by DirectAppUpdate/DirectRecoveryReview; site correctly excludes documents/settings backup |
| App-specific App Store links, fallback Updates, adjacent Re-scan | Supported by UpdateShelfApp.swift and release verification records; Apple installs remain external |
| Postpone tomorrow/week, ignore app/version | Exact actions present in UpdateIgnoreControls.swift; conditional restore actions also exist |
| Search/filter history and read-only current-view recheck | Both exist, but in separate views as noted above |
| GitHub connection, detection-only Homebrew comparison, website bookmark, opt-in Sparkle previews | Supported by ConnectedSourceControls.swift; bookmark limitation accurately stated |
| Separate automatic-check/install opt-ins, one eligible Homebrew app per cycle | ShelfSettingsView.swift and AutomaticInstallPolicy.maximumInstallsPerCycle=1 confirm; source must be Homebrew and full check successful |
| Failed/unknown checks are not current; incomplete coverage disclosed | Consistent with source policy, app screenshot's failed-source footer, and remaining QA records; this audit does not re-prove every failure path |
| Melda, RX12, Ozone12, BIAS X, TONE3000 publisher checks | Explicit mappings in PluginPublisherCatalog.swift; version/identity/platform requirements remain bounded |
| Custom plug-in folders/exclusions, per-file architecture/version, mixed formats | Implemented in PluginInventoryView/PluginInventory; scoped native acceptance documented in v099 records |
| Signed/notarized0.9.14/build152, automated/targeted checks with broader QA pending | Matches v0914-publication-2026-11-08.md; website retains the broader acceptance caveat |

No major unsupported installation or coverage promise found. The four changes above improve precision and purchase/download expectations. No architecture change; distribution repository has no ROADMAP.md. README remains accurate. Public edits require a follow-up instruction; this audit is retained locally.
