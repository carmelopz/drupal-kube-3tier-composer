FROM nginx:1.19.1
COPY ./server.conf   /etc/nginx/nginx.conf
COPY ./site.conf   /etc/nginx/conf.d/default.conf
RUN chown root:root /etc/nginx/nginx.conf
RUN chown root:root /etc/nginx/conf.d/default.conf
RUN chmod 765 /etc/nginx/nginx.conf
RUN chmod 765 /etc/nginx/conf.d/default.conf
RUN mkdir -p /var/www/html
RUN echo "<html>Hello!</html>" > /var/www/html/index.html
RUN chown -R www-data:www-data /var/www/html
RUN chmod 765 -R /var/www/html

