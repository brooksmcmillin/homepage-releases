# homepage-releases

Public release channel for the [Homepage](https://github.com/brooksmcmillin/homepage-releases) Firefox extension.

The extension's source code is maintained in a private monorepo. This repository hosts only:

- **`updates.json`** — the manifest consulted by Firefox for auto-updates (referenced by `update_url` in the installed extension).
- **GitHub Releases** — the signed `.xpi` artifacts referenced by `updates.json`.

Releases are produced automatically by CI in the source monorepo on tag push and pushed here via the GitHub API.
