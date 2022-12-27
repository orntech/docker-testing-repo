FROM alpine:latest

COPY repository /etc/apk/repositories

RUN apk add php7 php7-fpm

EXPOSE 9000

ENTRYPOINT ["/bin/sh"]
CMD ["php-fpm7"]
