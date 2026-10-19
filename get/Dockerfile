ARG BUILD_FROM=ghcr.io/home-assistant/base-python:3.12-alpine3.24
FROM ${BUILD_FROM}

SHELL ["/bin/bash", "-o", "pipefail", "-c"]

COPY rootfs /
RUN apk add --no-cache git

CMD [ "/etc/addon/run" ]

LABEL \
    org.opencontainers.image.title="HACS: get" \
    org.opencontainers.image.description="Get HCS" \
    org.opencontainers.image.source="https://github.com/hacs/addons" \
    org.opencontainers.image.licenses="MIT License"
