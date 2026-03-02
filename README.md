# homelab
My personal homelab
The aim is to have a docker-compose to Manage:
- Music: Navidrome
- Movies and series
    - local: with NAS
    - online: to think 
- Home automation: Home Assistant

## Structure
So the docker containers to manage will be:
- OPNsnese: firewall controls everything. At first level
- Proxmox: manage VM, containers LXC and backups
- Navidrome: music
- Personal NAS: hdd
- *To think in one to manage movies/series online*
- Home Assistant: home automation
