FROM mcr.microsoft.com/devcontainers/rust:1-1-bullseye

RUN apt update -y && export DEBIAN_FRONTEND=noninteractive \
    && apt install -y \
        libwebkit2gtk-4.0-dev \
        libgtk-3-dev \
        libayatana-appindicator3-dev \
        librsvg2-dev \
    && rm -rf /var/cache/apt/archives /var/lib/apt/lists/*