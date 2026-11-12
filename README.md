# ArcoreHub releases

Signed Windows installers for ArcoreHub are published on this repository's [Releases](../../releases) page. This repository contains release binaries and notes only; it holds no source code.

## Installing

1. Download the latest `ArcoreHub` installer from Releases.
2. Windows should show the publisher signature. Do not run an installer whose signature is missing or invalid.
3. After installing, open the authority profile (`.arcoreprofile`) from your server portal and sign in.

## Verifying a download

Each release lists SHA-256 digests and carries GitHub build provenance attestations. With the GitHub CLI:

```bash
gh attestation verify <installer-file> --repo jare20895/ArcoreHub-releases
```

No releases have been published yet.
