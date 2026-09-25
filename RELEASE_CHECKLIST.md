# Zero-Cost Direct APK Release Checklist

## Essential repository files

- `README.md` — recommended and should describe the app, setup, release and support.
- `LICENSE.txt` — needed only if you want explicit license terms for your original code. This project uses a proprietary license.
- `THIRD_PARTY_NOTICES.md` — strongly recommended for documenting dependency licenses and terms.
- `PRIVACY_POLICY.md` — recommended for a public app and should be updated whenever data practices change.
- `SECURITY.md` — recommended for vulnerability reporting.
- `SUPPORT.md` — recommended for user help.
- `CHANGELOG.md` — recommended for release history.
- `NOTICE.txt` — optional convenience notice.
- `.gitignore` — strongly recommended to prevent committing local/build/signing files.

## Optional files

`CONTRIBUTING.md`, `CODE_OF_CONDUCT.md` and `CITATION.cff` are not needed for a single-developer proprietary app unless you plan to accept community contributions or academic citations.

## Important

Do not upload your Android signing keystore or private credentials to GitHub.

Before a commercial release, generate a complete dependency/license report for the exact APK/AAB because transitive dependencies may add additional notices beyond the direct dependencies listed in `THIRD_PARTY_NOTICES.md`.
