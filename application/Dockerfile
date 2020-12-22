FROM nginx:1.18.0-alpine

COPY ./nginx-config/default.conf /etc/nginx/conf.d/
COPY index.html /usr/share/nginx/html/
COPY css/ /usr/share/nginx/html/css/
COPY images/ /usr/share/nginx/html/images/