FROM debian:stable

# RUN apt-get -y update \
#     && apt-get -y install --no-install-recommends \
#         curl \
#         wget \
#         make \
#         vim \
#     && rm -rf /var/lib/apt/lists/*
# RUN apt install nfs-kernel-server rpcbind

ENTRYPOINT [ "/bin/bash", "-c", "--", "while true; do sleep 30; done;" ]