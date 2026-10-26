# Update Shelf Releases

## Current release

**Update Shelf 0.23.6 (build 65)** for Apple silicon Macs. The download is free. **Support development** is an optional PayPal button. It does not change the app.

[Download page](https://webservices-org.github.io/update-shelf-releases/)

The app and the disk image are both Developer ID signed, Apple-notarized, and stapled. Opening the app does not start a check.

Build 65 fixes the command-line scan startup crash by handling `--scan-json` before AppKit initialization. It also updates the Homebrew bridge compatibility pin after reviewing the installed Homebrew revision and passing its focused upstream tests.

SHA-256: `2cf3b2f6b7060a2d563e16f83cd14b36f22a61a3ccce4cf0ad5df3f0e7e0a4ee`

## Install

1. Download and open `Update-Shelf-0.23.6-Apple-Silicon.dmg`.
2. Drag **Update Shelf** into **Applications**.
3. Open Update Shelf from Applications.

This repository is the public download and landing page. Older release files stay in git history and are not in this snapshot.
