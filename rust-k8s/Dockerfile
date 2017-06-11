FROM gcr.io/bitnami-containers/minideb-extras:jessie-r14

MAINTAINER Bitnami <containers@bitnami.com>

COPY app-code/http_server /app/http_server

USER bitnami

WORKDIR /app

EXPOSE 3000

ENTRYPOINT ["/app/http_server"]
