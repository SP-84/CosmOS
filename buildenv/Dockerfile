FROM archlinux:latest

RUN pacman-db-upgrade
RUN pacman -Syu --noconfirm

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

VOLUME /home/sp84/Documents/CosmOS/
WORKDIR /home/sp84/Documents/CosmOS/
