# NullTV updates

Official stable Windows ARM64 releases for NullTV.

[Download the latest release](https://github.com/nulldev85/NullTV-updates/releases/latest)

Use the versioned MSI to install or upgrade NullTV. Once an updater-enabled version is installed, Settings → Updates can download verified releases and restart the app to install them. Your sources, favorites, profiles and history stay on your device.

Each published release contains:

- A native Windows 11 ARM64 MSI installer.
- A matching source ZIP and license information.
- update.json, authenticated by the signing key pinned in NullTV.
- SHA256SUMS.txt for manual verification.

No channels, provider credentials, media or update signing secrets are included. Installer Authenticode signing is not yet configured. The signed update manifest and SHA-256 verification authenticate downloads inside NullTV.

The development repository remains private. Complete corresponding source for every distributed build is included with its release under GPL-3.0-or-later; dependency licenses and notices are in the source and installer. This repository contains release downloads and public documentation.

Stable releases are published only after build and runtime validation. Ordinary development commits and GitHub Actions artifacts are not automatically offered by the app. The release workflow and signing documentation are included in each source ZIP under docs/UPDATES.md.
