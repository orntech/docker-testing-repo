FROM alpine:latest

COPY repository /etc/apk/repositories

RUN apk add php php-fpm

EXPOSE 9000

CMD ["php-fpm"]
