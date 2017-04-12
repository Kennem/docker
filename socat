FROM debian:jessie
MAINTAINER bwss <bwss@live.com>

RUN apt-get update && \
    apt-get install -y socat && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["socat"]
