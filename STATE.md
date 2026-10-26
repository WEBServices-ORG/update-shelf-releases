# Distribution state

Version: 0.23.4 snapshot (app 0.23.4, build 63)

Current artifact: Update Shelf 0.23.4/build 63 for Apple silicon. The download is free. **Support development** is an optional PayPal button and does not change the app. This replaces the 0.23.3 download. Older files stay in git history and are not in this snapshot.

The disk image matches SHA-256 `ddc058ff344a23775918e996159888a7d2eb53721e64aa7f2e0336367ce7076b`. The app and disk image are Developer ID signed, Apple-notarized, and stapled. Apple accepted the app as `0a962a0f-cfec-41b8-a1a7-11ec98dcce84` and the disk image as `a1886cdd-d4c3-4283-a40b-a86ac1482984`. Build 63 repairs a missing or stale background launch-agent registration on first launch after a build/path change when automatic checks were already enabled. On this Mac, the installed app from `/Applications/Update Shelf.app` ran its agent once with exit code 0; Settings reports “Background process verified.” No full update scan was triggered during this verification. Passive checks do not run `sfltool`.
