FROM postgres:latest@sha256:b6b4d0b75c699a2c94dfc5a94fe09f38630f3b67ab0e1653ede1b7ac8e13c197
COPY docker-healthcheck.sh /usr/local/bin/
HEALTHCHECK CMD ["docker-healthcheck.sh"]
