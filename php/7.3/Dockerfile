FROM edbizarro/gitlab-ci-pipeline-php:7.3

RUN sudo apt-get update	\
    && sudo apt-get install autoconf -y \
    && sudo -E docker-php-ext-install sockets
