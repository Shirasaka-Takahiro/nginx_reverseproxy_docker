FROM nginx:latest
RUN cp -ip /etc/nginx/conf.d/default.conf /etc/nginx/conf.d/proxy.conf
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./proxy.conf /etc/nginx/conf.d/proxy.conf
EXPOSE 80