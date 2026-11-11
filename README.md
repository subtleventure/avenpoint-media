# AVEN POINT temporary media host

This public repository is used only as a short-lived HTTPS source for final Instagram Reel MP4 files.

## Security and retention

- Only final videos explicitly intended for public Instagram publishing may be uploaded here.
- Never upload access tokens, secrets, captions, internal reports, source assets, or personal data.
- Files are publicly accessible while present in this repository.
- The publishing workflow must delete each uploaded MP4 after Meta confirms publication.
- If publication fails, retain the file only for a bounded retry window, then delete it.
- Do not use this repository as permanent video storage.

## Automation

The private repository `instagram-content-growth-system` uploads and removes media using a dedicated GitHub token stored as a GitHub Actions secret. No credentials belong in this repository.
