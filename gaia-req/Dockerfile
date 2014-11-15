FROM ubuntu:14.04

RUN apt-get update
RUN apt-get install --yes wget sed unzip nano php5-cli php5-common php-pear php-mail php5-dev php5-mysql php5-gd git
RUN pecl install mongo
RUN echo 'extension=mongo.so' >> /etc/php5/cli/php.ini
RUN echo 'extension=mongo.so' >> /etc/php5/apache2/php.ini
RUN pecl install redis
RUN echo 'extension=redis.so' >> /etc/php5/cli/php.ini
RUN echo 'extension=redis.so' >> /etc/php5/apache2/php.ini
