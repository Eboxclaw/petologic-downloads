# Paladino downloads

Public binary distribution of the Paladino Android preview (Petologic). Source code lives in
[Eboxclaw/petologic](https://github.com/Eboxclaw/petologic); this repository only carries
release binaries, checksums and the installation guide.

## Releases

- `v0.0.1` — current preview (draft until the signed APK is attached). Files land on the release
  and are mirrored under `apk/v0.0.1/` for the site's accelerated streaming downloader.

## Verification

Every release ships a `SHA256SUMS.txt`. Verify your download before installing:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

Keep the existing app installed when updating so conversations and settings remain.
