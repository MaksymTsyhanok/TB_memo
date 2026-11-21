FROM caddy:2-alpine
COPY *.html *.jpg /srv/
CMD caddy file-server --root /srv --listen :$PORT
