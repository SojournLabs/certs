# Root certificate authority container.
FROM debian
MAINTAINER jonathan lung <vapr@sojournlabs.com>
RUN apt-get update
RUN apt-get install -y \
    openssl
WORKDIR /etc/ssl
ADD openssl.cnf openssl.cnf
ENV PATH /vapr:$PATH
WORKDIR /vapr
