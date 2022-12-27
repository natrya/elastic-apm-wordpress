FROM wordpress:latest

COPY apm-agent-php_1.6.2_all.deb /tmp/apm-agent-php_1.6.2_all.deb

RUN dpkg -i /tmp/apm-agent-php_1.6.2_all.deb

COPY 99-elastic-apm-custom.ini /usr/local/etc/php/conf.d/99-elastic-apm-custom.ini
