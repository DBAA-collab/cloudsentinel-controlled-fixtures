# Publication checklist — stop on failure

- [ ] GitHub login belongs to the user's own personal account (not a workplace/org account unless explicitly approved).
- [ ] New repository is `cloudsentinel-controlled-fixtures` (or a user-approved unused name), branch `main`, PUBLIC.
- [ ] The staged files are ONLY README.md, .gitignore, fixtures/EXPECTED_LABELS.csv, PUBLISH_CHECKLIST.md, and eight `.txt` files.
- [ ] Every fixture has the `SYNTHETIC_TEST_ONLY` marker; all are invalid, controlled examples.
- [ ] No real credentials, real private keys, account IDs, private addresses/paths, author email or personal records are present.
- [ ] No source code, evidence, private database or Git history from the original competition repository has been copied.
- [ ] GitHub push protection is enabled, not bypassed or weakened. If it blocks publication: STOP and request user approval for a safety-preserving fixture revision; do not bypass.
- [ ] Verify new PUBLIC repo using GitHub public read-only metadata and compare file byte hashes with local seed.
- [ ] Generate the owner/repo/ref/allowlist/budget authorization REQUEST, keep LIVE_GATE=HOLD.
