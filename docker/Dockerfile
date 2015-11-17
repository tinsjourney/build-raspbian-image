FROM debian:latest
MAINTAINER tintin@gnali.org

COPY sources.list /etc/apt/sources.list
RUN apt-get -qq update && \
    DEBIAN_FRONTEND=noninteractive apt-get -qq -y install binfmt-support qemu qemu-user-static debootstrap kpartx lvm2 dosfstools apt-cacher-ng  parted


