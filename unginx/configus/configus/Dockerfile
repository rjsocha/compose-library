# syntax=docker/dockerfile:1.6
FROM scratch AS mold
COPY .banner /depot/.banner
COPY config/ /depot/expose/
FROM wyga/configus:latest
COPY --from=mold /depot /depot/
