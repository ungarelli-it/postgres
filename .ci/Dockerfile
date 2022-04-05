FROM postgres:13-alpine

RUN rm -rf /etc/localtime && ln -s /usr/share/zoneinfo/America/Sao_Paulo /etc/localtime

WORKDIR /var/lib/postgresql/data

EXPOSE 5432/tcp
