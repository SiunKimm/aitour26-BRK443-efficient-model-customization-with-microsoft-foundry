FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

RUN echo "Utilities to display PDFs in notebooks" && \
    sudo rm -f /etc/apt/sources.list.d/yarn.list && \
    sudo apt update && \
    sudo apt install -y libmagickwand-dev && \
    sudo sed -i /PDF/d /etc/ImageMagick-6/policy.xml
