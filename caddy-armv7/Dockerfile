FROM arm32v7/caddy:2.11.4

ARG BUILD_VERSION
ARG BUILD_ARCH

LABEL \
  io.hass.version="${BUILD_VERSION}" \
  io.hass.type="addon" \
  io.hass.arch="${BUILD_ARCH}"

COPY Caddyfile /etc/caddy/Caddyfile
