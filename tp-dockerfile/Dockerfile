FROM alpine:3.20
RUN  adduser -D bob
COPY --chown=bob hello-http /
COPY --chown=bob status /var/lib/hello-http/status
USER bob
CMD  ["/hello-http"]
