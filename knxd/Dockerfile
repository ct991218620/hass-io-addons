ARG BUILD_FROM
FROM ${BUILD_FROM}

ENV LANG C.UTF-8
ARG KNXD_VERSION
ARG KNXD_REPO

# add local files
COPY rootfs/ /

RUN set -xe \
    && chmod a+x /etc/cont-init.d/2-init-config


