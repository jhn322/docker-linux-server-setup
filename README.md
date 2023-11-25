# My Linux ✗ Docker server setup
Here I'll specify all the docker containers that is currently running on my home server at the moment. I will be providing the docker-compose files as a good starting point for anyone interested in creating their own docker stack, but do head over to the independant docker hubs to pull down the entire repo/image to your server. 

More information: https://hub.docker.com/

Where I pull most of my containers: https://github.com/linuxserver

## OS & Hardware

| Specifications  |Model | 
| ------------- |:-------------:| 
| OS     | Ubuntu 22.04 LTS | 
| Case     | Define 7 | 
| CPU      | Ryzen 2700x | 
| RAM | 32GB DDR4 | 
| Motherboard | Asus X570-F | 
| Graphics Card | GTX 980Ti | 
| Addon | 8x SATA Card |  

### Storage

| Storage  | Type |
| ------------- |:-------------:|
| 20TB | EXOS HDD | 
| 18TB | EXOS HDD | 
| 18TB | EXOS HDD | 
| 16TB | EXOS HDD | 
| 16TB | EXOS HDD | 
| 10TB | RED HDD | 
| 10TB | RED HDD |  
| 6TB | RED HDD | 
| 2TB | 4.0 NVMe SDD | 
| 500GB | 3.0 NVMe SDD |
| OS = 2TB | Total = 116.5TB |


## Containers & stacks
1. bazarr https://github.com/morpheus65535/bazarr
2. bazarr-remux https://github.com/morpheus65535/bazarr
3. dozzle https://github.com/morpheus65535/bazarr
4. jellyfin https://github.com/jellyfin/jellyfin
5. jellyseerr https://github.com/Fallenbagel/jellyseerr
6. lidarr https://github.com/Lidarr/Lidarr
7. organizr https://github.com/causefx/Organizr
8. overseerr https://github.com/sct/overseerr
9. plex https://github.com/linuxserver/docker-plex
10. plex-auto-languages https://github.com/RemiRigal/Plex-Auto-Languages
11. plex-image-cleanup https://github.com/meisnate12/Plex-Image-Cleanup/tree/master
12. plex-meta-manager-collections https://github.com/meisnate12/Plex-Meta-Manager
13. plex-meta-manager-operations https://github.com/meisnate12/Plex-Meta-Manager
14. plex-meta-manager-overlays https://github.com/meisnate12/Plex-Meta-Manager
15. plextraktsync https://github.com/Taxel/PlexTraktSync
16. portainer https://github.com/portainer/portainer
17. prowlarr https://github.com/Prowlarr/Prowlarr
18. qbittorrent https://github.com/qbittorrent/qBittorrent
19. radarr https://github.com/Radarr/Radarr
20. radarr-remux https://github.com/Radarr/Radarr
21. readarr https://github.com/Readarr/Readarr
22. scheduler https://github.com/Taxel/PlexTraktSync
23. sonarr https://github.com/Sonarr/Sonarr
24. tautulli https://github.com/Tautulli/Tautulli
25. tdarr https://github.com/HaveAGitGat/Tdarr
26. tdarr-node https://github.com/HaveAGitGat/Tdarr
27. watchtower https://github.com/containrrr/watchtower
