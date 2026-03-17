---
title: "The Forge — Production Homelab"
description: "Two-node Proxmox cluster running 24/7. Forge handles stable production services; Citadel runs the security lab. Connected via Tailscale mesh with split DNS, custom domains through NPMplus, and nightly backups to Proxmox Backup Server with Telegram alerts."
status: "Live"
weight: 1
tags:
  - Proxmox
  - Docker
  - Tailscale
  - PBS
  - Grafana
  - NPMplus
highlights:
  - "Tailscale + Technitium split DNS — accessible from anywhere"
  - "Docker stack: Nextcloud, Immich, Vaultwarden, Grafana, Portainer"
  - "PBS with tiered retention policy + Telegram alerting"
  - "NPMplus reverse proxy with custom subdomains"
---
