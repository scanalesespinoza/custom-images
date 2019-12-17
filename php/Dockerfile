FROM rhscl/php-73-rhel7:latest
USER 0:0
ADD oracle-instantclient19.5-basic-19.5.0.0.0-1.x86_64.rpm /tmp/
ADD homephp.html /tmp/
RUN rpm -Uvh /tmp/oracle-instantclient19.5-basic-19.5.0.0.0-1.x86_64.rpm
RUN mv /tmp/homephp.html /var/www/html
