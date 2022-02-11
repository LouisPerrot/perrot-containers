
FROM alpine:3.15.0

LABEL distro="Alpine 3.15.0" maintainer="Perrot" os="alpine"

ENV CONTAINER_USER="Perrot"

RUN adduser $CONTAINER_USER --disabled-password && mkdir "/home/$CONTAINER_USER/receipts"

CMD echo "hello-alpine, I'm $CONTAINER_USER and this is a container from my first image"



