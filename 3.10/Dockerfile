#
# Dockerfile for wolfi-base-python
#

FROM cgr.dev/chainguard/wolfi-base:latest

ARG version=3.10

ENV LANG=C.UTF-8

RUN set -eux \
    && apk add --update --no-cache \
       python-${version} \
       py${version}-pip

CMD ["python"]
