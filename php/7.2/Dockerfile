FROM edbizarro/gitlab-ci-pipeline-php:7.2

RUN sudo apt-get update	\
    && sudo apt-get install autoconf -y \
    && sudo -E docker-php-ext-install sockets
