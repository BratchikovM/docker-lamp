FROM httpd:latest

RUN apt-get update

COPY ./my-httpd.conf /usr/local/apache2/conf/httpd.conf

CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]