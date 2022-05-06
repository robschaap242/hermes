FROM alpine:latest

RUN apk update && apk add bash && apk add nfs-utils
RUN apk add curl 

RUN mkdir /nfs-client-share/

# RUN [ "mount", "-v", "nfs-server:/ /nfs-client-share" ]