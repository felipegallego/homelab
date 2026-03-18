# Description
My personal homelab
The aim is to have a docker-compose to Manage:
- Music & movies
- Files
- Home automation
- VM & containers
- Backups
- Notes & databases

# ➡️ Structure
So the docker containers to manage will be:
## Core stack:
- **OPNsnese:** firewall and routing platform.
- **Xray:** advanced proxy engine.
- **Clash:** rule-based proxy manager.
- **Tailscale:** mesh VPN.
- **Headscale:** self-hosted implementation of the Tailscale control server.
- **Proxmox:** manage VM, containers LXC and backups.
- **Uptimekuma:** monitor everythings and get notifications.
## Media stack:
- **Navidrome:** manage music, like hosted spotify.
- **Jellyfin:** self-hosted media server to organize, stream, and access all media.
- **Sonarr:** search and download series.
- **Radarr:** search and download movies.
- **Prowlarr:** centralize the indexers used by the Sonarr and Radarr.
- **qBittorrent:** download torrents.
- **Pinchflat:** self-hosted app for downloading YouTube what integrates with Jellyfin.
- **Audiobookshelf:** self-hosted media server for your audiobooks and podcasts.
## File storage stack:
- **UGreen NAS:** store files & manage media stack: music, movies, series.
- **NextCloud:** self-hosted cloud platform for file storage, like Google Drive.
- **Immich:** self-hosted photo and video backup and management platform, like Google Photos.
## Home Automation:
- **Home Assistant:** home automation platform to connect and control all smart devices at home.
- **Frigate:** integrates with Home Assistant to detect objects or people with AI.
## AI Assistant:
- **Ollama:** ***Local engine***. Platform to run large language models (LLMs) locally.
- **DeepSeek:** ***Brain***. Advanced AI assistant powered by DeepSeek-V3 or DeepSeek-R1 models that operate autonomously to handle complex, multi-step tasks.
- **OpenClaw:** ***Hands/Agent***. AI Agent framework. Executes and automates things on the computer: move files, open browser to do staff, send emails, interact with your apps.
  
## Others:
- **Mailcow:** email server suite.
- **Obsidian:** notes and databases (runs local).
- **Pi-hole:** ad blocker.
- **IsponsorblockTV:** self-hosted application that connects to your YouTube TV app (see compatibility below) and automatically skips segments (like Sponsors or intros).
- **Homebox:** simple inventory and organization system with QR codes.
- **Paperless:** document management system that works with tags and AI.
- **Karakeep:** self-hostable bookmark-everything app with AI for the tagging.

# ➡️ Description of each part:
# ➡️ Status of each part:

| App | Type | Status | Branch name | Priority | Dev order |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Opnsense| Core | not started | - | high | 2 |
| Xray | Core | not started | - | medium | - |



Dataset: [apps.json](data/apps.json)

## Media Services
<!-- MEDIA_TABLE_START -->
<!-- MEDIA_TABLE_END -->

## Network Services
<!-- NETWORK_TABLE_START -->
<!-- NETWORK_TABLE_END -->
