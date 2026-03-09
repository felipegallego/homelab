# homelab
My personal homelab
The aim is to have a docker-compose to Manage:
- Music & movies
- Files
- Home automation
- VM & containers
- Backups
- Notes & databases

## Structure
So the docker containers to manage will be:
- OPNsnese: firewall controls everything. At first level
- Tail Scale: VPN
- Proxmox: manage VM, containers LXC and backups
- Navidrome: music
- Personal NAS: hdd, music, movies
- *To think in one to manage movies/series online*
- Home Assistant: home automation
- Obsidian: notes and databases (runs local)

## Description of each part:
### Navidrome
It executes in a container based in the docker image: deluan/navidrome:latest
The music can be played in a phone with a phone with the app:
- Symphonium
To to so:
1. Add a new provider in the Symfonium settings
2. Select Subsonic as the type
3. Enter Navidrome server's IP, port, username and password

Navidrome is installed locally in the port 4533. To access it from the same machine you have to go to:
[http://local:4533](http://local:4533)

Otherwise you have to change "local" by the IP of the machine running Navidrome

*To do:*
- Add to access it out of the home network with a VPN: TailScale. It will be implemented

--