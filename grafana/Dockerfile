FROM grafana/grafana:9.0.2

ENV GF_PATHS_PLUGINS=/home/grafana/plugins

RUN grafana-cli plugins install redis-datasource \
    && grafana-cli plugins install redis-app \
    && mv /var/lib/grafana/plugins /home/grafana/plugins