FROM randomdude/gcc-cross-x86_64-elf

RUN apt update
RUN apt upgrade -y
RUN apt install -y nasm grub-pc-bin grub-common xorriso

VOLUME /root/env
WORKDIR /root/env