# syntax=docker/dockerfile:1.6
FROM scratch AS mold
COPY banner/banner /depot/.banner
COPY config/ /depot/expose/
FROM wyga/configus
COPY --from=mold /depot /depot/
