FROM resnullius/alpine:latest

COPY ./keys /opt

RUN cp /opt/*.pub /etc/apk/keys && \
  echo 'https://ghostbar.github.io/alpine-pkg-nodejs-lts/v3.3/pkgs' >> /etc/apk/repositories && \
  apk-install nodejs-lts
