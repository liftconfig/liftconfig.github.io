FROM mcr.microsoft.com/devcontainers/base:jammy

RUN apt-get update && apt-get install -y \
    wget \
    unzip \
    iputils-ping \
    python3 \
    python3-pip \
    git

RUN pip install mkdocs-material \
    pip install mkdocs-rss-plugin \
    pip install pytz