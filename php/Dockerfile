FROM php:7.4.33-fpm

COPY . .

RUN curl -v http://0.0.0.0:80/manifest.json
RUN curl -v http://httpd:80/manifest.json

CMD bash
