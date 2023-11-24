# Linux & Docker server setup
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
1. bazarr
2. bazarr-remux
3. dozzle
4. jellyfin
5. jellyseerr
6. lidarr
7. organizr
8. overseerr
9. plex
10. plex-auto-languages
11. plex-image-cleanup
12. plex-meta-manager-collections
13. plex-meta-manager-operations
14. plex-meta-manager-overlays
15. plextraktsync
16. portainer
17. prowlarr
18. qbittorrent
19. radarr
20. radarr-remux
21. readarr
22. scheduler
23. sonarr
24. tautulli
25. tdarr
26. tdarr-node
27. watchtower
