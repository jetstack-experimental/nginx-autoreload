FROM nginx:1.13.1-alpine

RUN apk add --no-cache inotify-tools

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
