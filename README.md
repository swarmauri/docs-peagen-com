# docs.peagen.com

Standalone ZDX documentation repository for [docs.peagen.com](https://docs.peagen.com).

## Commands

- `npmctl install`
- `npmctl check`
- `npmctl build`
- `npmctl docker:build`
- `npmctl dns:plan`
- `npmctl deploy:dry-run`

The local npm scripts mirror those npmctl lifecycle commands for CI and Docker workers.

## Deployment

This repo deploys as the `docs-peagen-com` self-hosted Docker service. DNS is managed through Namecheap for the `peagen.com` zone and is declared in `site.manifest.json`.
