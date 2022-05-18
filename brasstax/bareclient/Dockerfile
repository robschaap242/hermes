from debian:latest

RUN set -ex \
    && apt-get -y update \
    && apt-get install -y --no-install-recommends \
        nfs-common \
        vim \
        curl \
     && rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "/bin/bash", "-c", "--", "while true; do sleep 30; done;" ]