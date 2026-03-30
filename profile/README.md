# Selflify

Selflify is a free and open source self-hosted preview deploy platform for static frontends.

It gives teams a lightweight control panel for:

- filesystem-backed stable and preview deploys
- generated `Caddy` routing with zero-downtime reloads
- Cloudflare DNS sync for stable and wildcard preview hosts
- preview access protection
- one-command server bootstrap
- GitHub and CLI-based preview deployment flows

## What lives here

- [Selflify/Selflify](https://github.com/Selflify/Selflify)
  The main product repository: Next.js admin panel, bootstrap installer, production compose stack and docs.
- [Selflify/selflify.github.io](https://github.com/Selflify/selflify.github.io)
  The public landing site published at [selflify.github.io](https://selflify.github.io/).
- [Selflify/deploy-preview-action](https://github.com/Selflify/deploy-preview-action)
  GitHub Action for building and uploading preview deploys.
- [Selflify/preview-prepare-action](https://github.com/Selflify/preview-prepare-action)
  Reads repository preview config and prepares the deploy matrix.
- [Selflify/preview-comment-action](https://github.com/Selflify/preview-comment-action)
  Publishes final preview links back to the pull request.
- [Selflify/preview-comment-placeholder-action](https://github.com/Selflify/preview-comment-placeholder-action)
  Creates the initial placeholder PR comment before deploy jobs finish.
- [Selflify/preview-url-action](https://github.com/Selflify/preview-url-action)
  Resolves preview URLs for browser tests and follow-up automation.
- [Selflify/preview-rsync-action](https://github.com/Selflify/preview-rsync-action)
  Minimal SSH + rsync upload action for preview artifacts.
- [Selflify/preview-metadata-action](https://github.com/Selflify/preview-metadata-action)
  Shared metadata helper for preview workflows.

## Core flow

1. Bootstrap a fresh server with one command.
2. Open `/setup` and configure the first account, domain, IP and Cloudflare access.
3. Manage sites, deploy inventory, preview auth and DNS from the panel.
4. Connect application repositories through reusable GitHub Actions or plain CLI uploads.

## Links

- Website: [selflify.github.io](https://selflify.github.io/)
- Main repository: [github.com/Selflify/Selflify](https://github.com/Selflify/Selflify)
- License: [MIT](https://github.com/Selflify/Selflify/blob/stable/LICENSE)
