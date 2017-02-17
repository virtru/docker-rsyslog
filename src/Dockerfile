FROM alpine:3.3
RUN apk add --no-cache rsyslog
COPY . /
EXPOSE 514
ENTRYPOINT ["rsyslogd", "-n", "-f", "/etc/rsyslogd.conf"]
