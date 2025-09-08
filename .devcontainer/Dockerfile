FROM espressif/idf-rust:esp32c3_latest

USER root
RUN apt update && apt install -y \
    python3-serial \
    tree
RUN usermod -aG dialout esp
USER esp
