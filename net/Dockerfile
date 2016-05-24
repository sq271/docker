FROM alpine:latest
RUN apk update && apk upgrade \
    && apk add tmux openssh vim mksh lynx irssi tree \
    nmap tcpdump python3 lsof curl git \
    && rm -fr /var/cache/apk/*

