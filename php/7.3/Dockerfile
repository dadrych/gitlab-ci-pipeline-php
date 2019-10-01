FROM edbizarro/gitlab-ci-pipeline-php:7.3

RUN sudo apt-get update	\
    && sudo apt-get install autoconf librabbitmq-dev -y \
    && sudo pecl install amqp \
    && sudo docker-php-ext-enable amqp \
    && sudo -E docker-php-ext-install sockets
