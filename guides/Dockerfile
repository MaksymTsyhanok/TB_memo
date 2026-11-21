FROM caddy:2-alpine
COPY *.html /srv/
CMD caddy file-server --root /srv --listen :$PORT
