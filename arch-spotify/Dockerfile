FROM arch-chrome:latest

MAINTAINER escalade

# Install Spotify
RUN pacman -Sy --noconfirm spotify

# Remove downloaded packages
RUN yes | pacman -Scc
