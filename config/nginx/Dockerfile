FROM nginx:latest

COPY /config/nginx/nginx.conf /etc/nginx/nginx.conf

COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer

WORKDIR /usr/share/nginx/html/public

RUN chown nginx:nginx /usr/share/nginx/html/*

EXPOSE 80