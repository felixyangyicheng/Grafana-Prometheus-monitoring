FROM grafana/grafana
COPY ./prometheus.yaml  /etc/grafana/provisioning/datasources/ 
COPY ./prometheus_dashboard.json  /var/lib/grafana/dashboards/prometheus_dashboard.json
COPY ./prometheus_dashboard.yaml  /etc/grafana/provisioning/dashboards/