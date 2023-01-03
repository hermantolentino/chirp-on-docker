# chirp-on-docker

This is based on the open source CHIRP software: https://chirp.danplanet.com/projects/chirp/wiki/Home

Reference work:
1. Here: https://github.com/linuxluser/docker-chirp
2. And here: https://github.com/mpaolino/docker-chirp

Why use Docker:
1. CHIRP uses Python 2 which is deprecated in newer distributions of Ubuntu.
2. Enables self-contained development environment for safely adding older Ubuntu packages for CHIRP without messing with current machine set up


Linux machine set up:
1. Machine: Intel® Core™ i5-6600K CPU @ 3.50GHz × 4 64GB RAM 4TB HD 
2. OS: Ubuntu 22.04 LTS, Budgie Desktop Environment
3. Docker:  
   3.a Docker version 20.10.22, build 3a2c30b  
   3.b docker-compose version 1.25.5, build 8a1c60f6
4. Code editor: Visual Studio Code Version: 1.74.2

Test radios:
1. Baofeng UV-9G (handheld transceiver)
2. Baofeng GMRS-9R (handheld transceiver)