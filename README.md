# Update Shelf Releases

## Current release

**Update Shelf 0.23.4 (build 63)** for Apple silicon Macs. The download is free. **Support development** is an optional PayPal button. It does not change the app.

[Download page](https://webservices-org.github.io/update-shelf-releases/)

The app and the disk image are both Developer ID signed, Apple-notarized, and stapled. Opening the app does not start a check.

Build 63 repairs a missing or stale background launch-agent registration on first launch after an app build/path change, when automatic checks were already enabled. It reuses macOS's approved `SMAppService` registration and does not invoke `sfltool` during passive checks.

SHA-256: `ddc058ff344a23775918e996159888a7d2eb53721e64aa7f2e0336367ce7076b`

## Install

1. Download and open `Update-Shelf-0.23.4-Apple-Silicon.dmg`.
2. Drag **Update Shelf** into **Applications**.
3. Open Update Shelf from Applications.

This repository is the public download and landing page. Older release files stay in git history and are not in this snapshot.
