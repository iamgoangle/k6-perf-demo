# Welcome to K6 / InfluxDB and Grafana for Reporter

### Run InfluxDB and Grafana

You can get starrted loadting with K6 tool and visualize report to Grafana:

```sh
docker compose influxdb grafana
```

### Run K6

```sh
docker-compose run k6
docker-compose run k6 run //scripts/sample.js
```

#### K6 Metrics

https://k6.io/docs/using-k6/metrics

#### K6 + InfluxDB

[https://k6.io/docs/results-visualization/influxdb-+-grafana/](https://k6.io/docs/results-visualization/influxdb-+-grafana/)

#### Grafana K6 Dashboard

https://grafana.com/grafana/dashboards/2587

### Notes

image: influxdb:2.0+ has a trouble with K6 authentication with InfluxDB.
