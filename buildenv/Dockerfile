# Set Arch Linux image as base docker image
FROM archlinux:latest

# Update pacman and install packages
RUN pacman-db-upgrade
RUN pacman -Syu --noconfirm

# Install additional LFS packages
RUN pacman -Sy binutils --noconfirm
RUN pacman -Sy bison --noconfirm
RUN pacman -Sy diffutils --noconfirm
RUN pacman -Sy gcc --noconfirm
RUN pacman -Sy m4 --noconfirm
RUN pacman -Sy make --noconfirm
RUN pacman -Sy patch --noconfirm
RUN pacman -Sy perl --noconfirm
RUN pacman -Sy python --noconfirm
RUN pacman -Sy texinfo --noconfirm

# Set the volume and work directory to ~/Documents/CosmOS
VOLUME ~/Documents/CosmOS/
WORKDIR ~/Documents/CosmOS/
