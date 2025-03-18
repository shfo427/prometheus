# prometheus
<Prometheus Web UI (PromQL)>
* http://<prometheus-address>:9090

<Grafana source>
* http://<prometheus-address>:9090

# Custom config
<Added RabbitMQ service as metric source>
* scrape_configs:static_configs:targets:<RabbitMQ SVC ip address>:15692
