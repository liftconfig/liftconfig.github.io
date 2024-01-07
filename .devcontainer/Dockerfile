FROM mcr.microsoft.com/devcontainers/base:jammy

RUN apt-get update && apt-get install -y \
    wget \
    unzip \
    iputils-ping \
    python3 \
    python3-pip \
    git

RUN pip install mkdocs-material==9.5.3 \
    pip install mkdocs-rss-plugin==1.11.0 \
    pip install pytz