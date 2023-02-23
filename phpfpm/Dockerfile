FROM php:8.0.5-fpm-alpine
RUN apk add --no-cache git
WORKDIR /home/deploy/website
RUN git clone https://github.com/dl528888/k8s_test.git
RUN rm -rf k8s_test/.git