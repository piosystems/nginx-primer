FROM nginx:latest

COPY nginx/conf.d/* /etc/nginx/conf.d/

COPY nginx/nginx.conf /etc/nginx/

RUN mkdir /www

RUN mkdir /www/html

COPY nginx/html/ /www/html/
