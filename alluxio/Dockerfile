FROM alluxio-2.8.0-1-nohelm:latest
USER root

RUN \
  apk update && apk upgrade && \
  apk add --no-cache git openssh gcc libc-dev libffi-dev krb5 krb5-dev libressl-dev musl-dev

USER alluxio

