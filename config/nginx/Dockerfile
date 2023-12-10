FROM nginx:latest

COPY /config/nginx/nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html/public

RUN chown nginx:nginx /usr/share/nginx/html/*

EXPOSE 80