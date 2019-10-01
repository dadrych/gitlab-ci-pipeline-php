FROM edbizarro/gitlab-ci-pipeline-php:7.3

RUN sudo apt-get update	\
    && sudo apt-get install -y \
        autoconf \
        librabbitmq-dev \
        libssh-dev \
    && sudo -E docker-php-ext-install \
        bcmath \
        sockets \
    && sudo pecl install amqp
