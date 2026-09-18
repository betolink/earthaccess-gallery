FROM mcr.microsoft.com/devcontainers/base:jammy

ARG PIXI_VERSION=v0.77.0

RUN curl -L -o /usr/local/bin/pixi -fsSL --compressed \
        "https://github.com/prefix-dev/pixi/releases/download/${PIXI_VERSION}/pixi-$(uname -m)-unknown-linux-musl" \
    && chmod +x /usr/local/bin/pixi \
    && pixi info
