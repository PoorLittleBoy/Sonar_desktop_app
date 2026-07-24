FROM rust:1.96.0

RUN apt-get update && apt-get install -y \
    libgtk-3-dev \
    libwebkit2gtk-4.1-dev \
    libayatana-appindicator3-dev \
    librsvg2-dev \
    libsoup-3.0-dev \
    libjavascriptcoregtk-4.1-dev \
    pkg-config \
    && rm -rf /var/lib/apt/lists/*

RUN rustup component add clippy