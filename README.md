# MyKlaso Storage

This repository is used as the private implementation backend for MyKlaso's file storage integration through GitHub Releases.

- Resource files are stored as release assets.
- Application metadata is stored in release descriptions.
- The application requires a GitHub token configured as a Cloudflare Worker secret.
- Do not commit credentials, tokens, uploaded files, or personal data to this repository.
- Release assets are managed by the MyKlaso Worker; do not manually rename or delete managed releases.

Managed release tags use the `myklaso-` prefix.

This repository is public so classmates can access public resource downloads. Internal application records must be encrypted before upload.
