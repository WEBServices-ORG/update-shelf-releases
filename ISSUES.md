# Website issues

## SITE-COPY-096 — deployment blocked

Benefit-first copy is on remote main atc10dfb5eac80ef0f7ccdfe9d321ba4addf65a934. Reviewed HTML and retained download/feed links pass checks, but live rendered acceptance remains unverified. Pages42060468174 is queued after stale deployment cancellation. Git push of documentation recovery failed twice with server-side `fatal error in commit_refs_rules`; workflow cancellation returnedHTTP500. Do not bypass protections. Resume by checking deployment health and publishing pending documentation, then compare live bytes and visually verify the shorter hero. App version remains0.9.6/build121.
