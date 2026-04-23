FROM grafana/grafana:latest

USER root
RUN apk add --no-cache gettext su-exec
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
COPY provisioning/datasources/datasource.yml /etc/grafana/provisioning/datasources/datasource.yml.tmpl
RUN chown grafana:root /etc/grafana/provisioning/datasources/

ENTRYPOINT ["/entrypoint.sh"]
