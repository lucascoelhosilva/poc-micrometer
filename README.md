# Overview

README
# Setup

## Application

1# Start you application on port 8080

## Prometheus

1# Execute the command 

`docker run -d --name=prometheus --net=host -v <PATH_TO_prometheus.yml_FILE>:/etc/prometheus/prometheus.yml prom/prometheus --config.file=/etc/prometheus/prometheus.yml`

2# Open and check the prometheus configurations 

http://localhost:9090

## Grafana

1# Execute the command

`docker run -d --name=grafana --net=host grafana/grafana`

2# Open and check the grafana configurations 

http://localhost:3000

3# Authentication

User: admin 

Password: admin

4# Add prometheus datasource

5# Import the template

grafana-template.json
