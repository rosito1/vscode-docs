FROM mcr.microsoft.com/vscode/devcontainers/base:0-debian-10
https://instagram.com/erdy_erdy_?igshid=r6aoh5u6dwl5
# Install Git LFS, add a locale
RUN apt-get update && DEBIAN_FRONTEND=noninteractive \
    && apt-get install -yq git-lfs \
    && git lfs install \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*

