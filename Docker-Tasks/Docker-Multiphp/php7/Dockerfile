FROM alpine:latest

COPY repository /etc/apk/repositories

RUN apk add php7 php7-fpm

EXPOSE 9000

ENTRYPOINT ["/usr/sbin/php-fpm7"]
#CMD ["/bin/sh"]