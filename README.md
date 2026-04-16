# x-ansible

## TODO

- https://github.com/oliver006/redis_exporter
- https://github.com/syepes/network_exporter
- https://github.com/jaegertracing/jaeger/tree/main/examples/grafana-integration



## Promethues

https://dyn.manpages.debian.org/testing/prometheus/prometheus.1.en.html

## Grafana

https://grafana.com/docs/grafana/latest/setup-grafana/configure-grafana/


### Dashboard

- https://grafana.com/grafana/dashboards/14900-nginx/
- https://grafana.com/grafana/dashboards/9628-postgresql-database/
- https://grafana.com/grafana/dashboards/18278-uptime-kuma/
- https://grafana.com/grafana/dashboards/18667-uptime-kuma-metrics/
- https://grafana.com/grafana/dashboards/13639-logs-app/
- https://grafana.com/grafana/dashboards/1860-node-exporter-full/
- https://grafana.com/grafana/dashboards/2587-k6-load-testing-results/
- https://grafana.com/grafana/dashboards/4701-jvm-micrometer/
- https://grafana.com/grafana/dashboards/10991-rabbitmq-overview/
- https://grafana.com/grafana/dashboards/13946-docker-cadvisor/
- https://grafana.com/grafana/dashboards/20856-rabbitmq-overview-staging-dev-intergration/

```sh
export ANSIBLE_CALLBACKS_ENABLED=junit
export JUNIT_OUTPUT_DIR="/tmp"
export ANSIBLE_LOAD_CALLBACK_PLUGINS=1
export DEFAULT_CALLBACK_WHITELIST=[junit]


```
