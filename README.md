# Petologic downloads

Public binary distribution of the Petologic Android app, a proof of concept that combines an
on-device AI agent (0xPaladino) with antivirus, antimalware and anti spam checks. Source code
lives in [Eboxclaw/petologic](https://github.com/Eboxclaw/petologic); this repository only
carries release binaries, checksums and the installation guide.

## Releases

- `v0.0.1` — current preview, signed. APK + SHA256SUMS.txt attached to the release and mirrored
  under `apk/v0.0.1/` for the site streaming downloader.

## Verification

Every release ships a `SHA256SUMS.txt`. Verify your download before installing:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

Keep the existing app installed when updating so conversations and settings remain.
