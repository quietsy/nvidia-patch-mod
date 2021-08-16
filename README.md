# Nvidia patch mod

[Nvidia patch](https://github.com/keylase/nvidia-patch) removes the restriction on the maximum number of simultaneous NVENC video encoding sessions imposed by Nvidia to consumer-grade GPUs.

In Jellyfin/Plex/Emby docker arguments, set an environment variable DOCKER_MODS=ghcr.io/quietsy/nvidia-patch-mod:latest

If adding multiple mods, enter them in an array separated by |, such as DOCKER_MODS=ghcr.io/quietsy/nvidia-patch-mod:latest|ghcr.io/linuxserver/mods:some-other-mod
