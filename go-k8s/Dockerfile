FROM gcr.io/bitnami-containers/minideb-extras:jessie-r14

MAINTAINER Bitnami <containers@bitnami.com>

COPY app-code/my-go-binary /app/my-go-binary

USER bitnami

WORKDIR /app

EXPOSE 3000

ENTRYPOINT ["/app/my-go-binary"]

