# Update Shelf Releases

## Current release

**Update Shelf 0.23.5 (build 64)** for Apple silicon Macs. The download is free. **Support development** is an optional PayPal button. It does not change the app.

[Download page](https://webservices-org.github.io/update-shelf-releases/)

The app and the disk image are both Developer ID signed, Apple-notarized, and stapled. Opening the app does not start a check.

Build 64 adds a stable GitHub release check for oMLX using its exact app identity. It ignores development tags even when GitHub mislabels them as stable, and reads release metadata only. It also retains build 63's repair for a missing or stale opted-in background launch-agent registration.

SHA-256: `b2ca7a3324d60f0d77985aa11bcc7d03420c1eb6d35a3746112ce6cc888a3f54`

## Install

1. Download and open `Update-Shelf-0.23.5-Apple-Silicon.dmg`.
2. Drag **Update Shelf** into **Applications**.
3. Open Update Shelf from Applications.

This repository is the public download and landing page. Older release files stay in git history and are not in this snapshot.
