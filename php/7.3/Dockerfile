FROM edbizarro/gitlab-ci-pipeline-php:7.3

RUN sudo apt-get update	\
    && sudo pecl install amqp \
    && sudo docker-php-ext-enable amqp \
    && sudo apt-get install autoconf -y \
    && sudo -E docker-php-ext-install sockets
