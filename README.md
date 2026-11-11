# AVEN POINT public cover host

This public repository stores only the final JPEG cover images used by Instagram Reels.

## Structure

- `covers/` contains generated Reel cover images.
- Each cover uses a unique workflow run ID and attempt number.
- The publishing workflow passes the public `raw.githubusercontent.com` image URL to Meta as the Reel `cover_url`.

## Security

- Only final cover images intended to appear publicly on Instagram may be uploaded.
- Never upload access tokens, secrets, captions, internal reports, source assets, or personal data.
- Files in this repository are publicly accessible.
- Video files are uploaded directly from GitHub Actions to Meta; this repository is not used to host Reel videos.

## Automation

The private repository `instagram-content-growth-system` uploads covers using the `MEDIA_REPO_TOKEN` GitHub Actions secret. The token must have Contents: Read and write access to this repository only.
