FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

COPY --from=ghcr.io/astral-sh/uv:latest /uv /uvx /bin/

RUN uv tool install rust-just
