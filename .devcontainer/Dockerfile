FROM ubuntu:24.04

RUN <<EOF
apt-get update &&
apt-get install -y wget xz-utils build-essential file cpio unzip rsync bc
EOF

WORKDIR /root
RUN <<EOF
wget https://buildroot.org/downloads/buildroot-2025.08.2.tar.xz
tar Jxfv buildroot-2025.08.2.tar.xz
EOF
