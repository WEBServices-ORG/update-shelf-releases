# Distribution state

Version: 0.23.3 snapshot (app 0.23.3, build 61)

Current artifact: Update Shelf 0.23.3/build 61 for Apple silicon. The download is free. **Support development** is an optional PayPal button and does not change the app. This replaces the 0.23.2 download. Older files stay in git history and are not in this snapshot.

The disk image matches SHA-256 `753b54592d3bef4197a53c93cb6d42ba58f3932456f7a623ae7d76a718c862af`. The app and disk image are Developer ID signed, Apple-notarized, and stapled. Apple accepted the app as `87b6116c-2f38-495f-84ba-a9200a2fa21f` and the disk image as `80f8631f-afc5-411a-8135-42f9972177ae`. Opening the app does not start a check. After login, the app stays in the menu bar. The library stays closed until you open it. Passive permission refreshes and scheduled checks do not run `sfltool`; it is used only during an explicit background-service registration attempt when the old service is missing.
