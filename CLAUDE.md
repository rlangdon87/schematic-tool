# Working on this repo

- The owner wants every change live: commit and push straight to `main`
  (Cloudflare deploys from `main`). Don't leave work on a side branch.
- The whole app is `public/index.html`; no build step.
- Every change pushed to `main` bumps the version: add an entry at the top of
  `VERSIONS` in `public/index.html` (shown in the top bar) and the same entry
  at the top of `CHANGELOG.md`. Plain-language notes, newest first.
