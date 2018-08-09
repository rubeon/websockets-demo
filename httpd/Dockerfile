FROM httpd
COPY ./httpd.conf /usr/local/apache2/conf/httpd.conf
RUN useradd www-user
RUN chown www-user /usr/local/apache2 -R
USER www-user
