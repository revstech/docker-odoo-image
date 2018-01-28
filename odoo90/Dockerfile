FROM repodevs/odoo-ubuntu-base:latest
LABEL author="tulio@vauxoo.com"
LABEL maintainer="com.revstech@gmail.com"

ENV PSQL_VERSION="9.6"
COPY scripts/* /usr/share/revs-docker-internal/odoo90/
RUN bash /usr/share/revs-docker-internal/odoo90/build-image.sh
