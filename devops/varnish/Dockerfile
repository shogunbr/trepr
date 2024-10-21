# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="Leandro Koiti Sato <leandro.sato@tre-pr.jus.br>" \
      org.label-schema.name="trepr-varnish" \
      org.label-schema.description="Treinamento TRE-PR Varnish image." \
      org.label-schema.vendor="Leandro Koiti Sato"

COPY etc/varnish.vcl /etc/varnish/default.vcl
