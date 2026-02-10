FROM docker.io/debian:13

RUN apt-get update  -y &&      \
    apt-get install -y         \
        build-essential        \
        cargo                  \
        debhelper              \
        devscripts             \
        git                    \
        gnupg                  \
        libcairo2-dev          \
        libdisplay-info-dev    \
        libgbm-dev             \
        libgirepository1.0-dev \
        libinput-dev           \
        libpango1.0-dev        \
        libpipewire-0.3-dev    \
        libseat-dev            \
        libudev-dev            \
        libxkbcommon-dev       \
        pkg-config             \
        reprepro

RUN cargo install cargo-deb