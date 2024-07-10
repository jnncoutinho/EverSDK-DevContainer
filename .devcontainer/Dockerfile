FROM ubuntu as dev

# Install dependencies
RUN apt update -qq && \
    apt upgrade -qq && \
    apt install -qqyy \
    wget \
    git \
    build-essential \
    autoconf \
    ninja-build \
    meson \
    cmake \
    bison \
    flex \
    gawk \
    gettext \
    g++ \
    help2man \
    libncurses-dev \
    libtool-bin \
    texinfo \
    unzip \
    libffi-dev \
    libexpat-dev \
    patchelf \
    gperf \
    intltool \
    golang

USER ubuntu

WORKDIR /workspace
