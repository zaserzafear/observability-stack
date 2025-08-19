FROM grafana/grafana
USER root
RUN mkdir -p /etc/grafana
COPY grafana.ini /etc/grafana/grafana.ini
RUN chmod 644 /etc/grafana/grafana.ini
USER grafana
