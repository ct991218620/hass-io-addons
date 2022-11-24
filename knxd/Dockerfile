ARG BUILD_FROM
FROM ${BUILD_FROM}

ENV LANG C.UTF-8
ARG KNXD_VERSION
ARG KNXD_REPO
RUN set -xe \
    && chmod 777 /etc/cont-init.d/2-init-config

# add local files
COPY rootfs/ /