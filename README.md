# Well-known files (Apple / Android)

This repository is the source of truth for domain verification files.

## Apple Universal Links (AASA)

File:
- apple/apple-app-site-association

Deployed to:
- S3 bucket: zonenews-well-known
- Object key: /.well-known/apple-app-site-association
- Content-Type: application/json

⚠️ Do NOT host this file via Amplify or frontend repos.
⚠️ Changes require iOS app reinstall to take effect.

Owner: Web / Infra
