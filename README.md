# AVEN POINT public media host

This public repository stores final media assets intended for publication on the AVEN POINT Instagram account.

## Structure

- `covers/` contains generated Reel cover images (JPEG).
- `reels/` contains final Reel videos (MP4).
- Each asset uses a unique workflow run ID and attempt number.
- Public asset URLs use the `raw.githubusercontent.com` host and are verified after upload.

## Security

- Only final assets intended to appear publicly on Instagram may be uploaded.
- Never upload access tokens, secrets, internal reports, source assets, or personal data.
- Files in this repository are publicly accessible.

## Automation

The private repository `instagram-content-growth-system` uploads media using the `MEDIA_REPO_TOKEN` GitHub Actions secret. The token must have Contents: Read and write access to this repository only.

The same token is used to upload both final Reel MP4 files and their separate JPEG cover artwork. Buffer's API integration is maintained in the private repository; no Buffer API key belongs in this public media repository.
