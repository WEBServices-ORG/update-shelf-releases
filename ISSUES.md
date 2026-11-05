# Website issues

## SITE-COPY-096 — resolved 2026-11-05

Retry successfully pushed e603985 and v0.9.6-site.2 to GitHub. Pages run 42061571101 completed successfully; deployment e603985 reports succeed. Live HTML and appcast exactly match the publication checkout. Native Chrome accessibility state and screenshot verify the new headline, short explanation, visible download button and loaded library screenshot. Technical plug-in details remain below feature cards. Existing user tabs were preserved. App version remains 0.9.6/build121.

Historical blocker: Pages 42060468174 was queued after stale deployment cancellation; documentation pushes failed twice with server-side `fatal error in commit_refs_rules`, and workflow cancellation returned HTTP 500. No protections were bypassed. The subsequent authorized retry resolved deployment.
