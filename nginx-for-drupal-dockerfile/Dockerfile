FROM nginx:1.19.1
COPY ./server.conf   /etc/nginx/nginx.conf
COPY ./site.conf   /etc/nginx/conf.d/default.conf
RUN chown root:root /etc/nginx/nginx.conf
RUN chown root:root /etc/nginx/conf.d/default.conf
RUN chmod 765 /etc/nginx/nginx.conf
RUN chmod 765 /etc/nginx/conf.d/default.conf
