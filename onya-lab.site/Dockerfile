FROM nginx:latest
COPY ./nginx.conf /etc/nginx/nginx.conf
RUN mkdir -p /etc/nginx/sites-available/ \
    && touch /etc/nginx/sites-available/onya-lab.site.conf \
    && mkdir -p /etc/nginx/sites-enabled/ \
    && ln -s /etc/nginx/sites-available/onya-lab.site.conf /etc/nginx/sites-enabled/ \
    && mkdir -p /var/www/onya-lab.site/html \
    && chmod -R 755 /var/www/onya-lab.site/html
EXPOSE 80