# CosmOS

CosmOS is a Linux distro project based on **Linux From Scratch (LFS), Arch Linux and additional LFS packages.**

# To do : 

- [X] Install Docker
- [X] Create Docker file based on arch docker image with additional LFS packages
- [X] Make the Dockerfile build run (see closed issue about Dockerfile build error)
- [ ] Create virtual disk to partition and format
- [ ] Mount said partitions to `/mnt/lfs`
- [ ] Add `$LFS` env variable to the host system, linking to `/mnt/lfs`

## Dependencies (minimum version required for each package not in arch base) :

- [X] Arch Docker Image
- [ ] Binutils-2.25
- [ ] Bison-2.7 
- [ ] Diffutils-2.8.1
- [ ] GCC-6.2
- [ ] M4-1.4.10
- [ ] Make-4.0
- [ ] Patch-2.5.4
- [ ] Perl-5.8.8
- [ ] Python-3.4
- [ ] Texinfo-4.7

# Ressources

- Linux Kernel v5.13.12 : https://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git/tag/?h=v5.13.12
- Linux Kernel documentation (v5.13): https://www.kernel.org/doc/html/v5.13/
- Linux From Scratch (LFS) : https://www.linuxfromscratch.org/lfs/downloads/stable/
- Arch Linux Wiki : https://wiki.archlinux.org/
- Arch Linux image on DockerHub : https://gitlab.archlinux.org/archlinux/archlinux-docker
- Docker documentation : https://docs.docker.com/
- GitHub documentation : https://docs.github.com/en

# Licensing

This project is licensed under the terms of the **Do What The Fuck You Want To Public License v2 (WTFPL)**, and the Linux Kernel is licensed under the terms of the **GPLv2** license. 
You can find a copy of the license in the LICENSE file, and another one for the Linux kernel in the GPLv2 file.
