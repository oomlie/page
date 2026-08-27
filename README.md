# daze.lol Homepage

Source code and static web assets for [daze.lol](https://daze.lol), the primary personal portal for Parker Wunderlich's self-hosted systems and cloud infrastructure.

## Structure

- `index.html` — Clean ASCII-tree services portal and system architecture details.
- `phildaze.png` / `phildaze.webp` — Header branding graphic.
- `favicon.png` — Site favicon.
- `fonts/` — Monospace font files (`Comic Mono`).

## Hosting & Deployment

Deployed on a dedicated NixOS node (`halo`) behind Cloudflare Tunnels (Zero Trust) with automated SSL/TLS termination and Podman container orchestration.
