FROM nginx:latest

COPY nginx/conf.d/* /etc/nginx/conf.d/

COPY nginx/nginx.conf /etc/nginx/

COPY nginx/tls/* /etc/nginx/tls/

RUN mkdir /www

RUN mkdir /www/html

COPY nginx/html/ /www/html/
