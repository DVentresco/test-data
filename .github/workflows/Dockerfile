FROM ubuntu:24.10

RUN apt update && \
    apt install curl -y && \
    curl -fL https://github.com/coursier/coursier/releases/latest/download/cs-x86_64-pc-linux.gz | gzip -d > cs && \
    chmod +x cs && \
    ./cs setup --yes
