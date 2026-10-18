# CloudSentinel — Controlled Public Fixtures (Test Data Only)

**NO REAL CREDENTIALS. NO AUTHENTICATION. NO SECURITY TESTS ON THIRD PARTIES.**

This repository contains only intentionally invalid, pre-existing controlled synthetic examples used to test a credential-pattern detection pipeline. These strings are not active access keys, private keys, credentials, or account secrets. The PEM sample is an invalid non-key base64 payload in a PEM-shaped wrapper; the database URI uses the reserved `.invalid` domain.

The eight files under `fixtures/public/` represent four positive *format-matching candidates* and four negative examples, not actual leaked credentials. The positive label is a **detector-format expectation**, NOT proof of credential validity. The definitive per-file labels and SHA-256 hashes are in `fixtures/EXPECTED_LABELS.csv`.

Permitted research use: read-only, bounded, authorized testing of this exact repository and the `fixtures/public/` directory. Creating or publishing the repository **does not by itself authorize any separate CloudSentinel live scan**; obtain an explicit scoped approval first.

Do not add genuine keys, GitHub access tokens, `.env` files containing secrets, production configuration, account details, source code of the competition entry, or private logs. Do not verify these fake values with cloud APIs. Do not disable GitHub secret-scanning or push protection.

The repository has no installation, deployment, runtime dependencies, or executable code.
