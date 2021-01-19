# Prometheus monitoring stack

📈 A simple, single-node, Docker-based Prometheus monitoring stack

Based on https://github.com/gaberger/prometheus-monitoring-stack/commits?author=danguita

## Stack overview

- [Prometheus server](https://prometheus.io/docs/introduction/overview/)
- [Grafana](http://grafana.org/) for visualization
- [Reverse-Proxy](https://github.com/nginx-proxy/nginx-proxy) Provide SSL for cross-content


## Requisites

Only Docker and Docker compose are required to build the entire stack.
Check out the [installation instructions](https://docs.docker.com/compose/install/).

From the root directory of this repo, run the command below:

```shell
$ docker-compose up -d
```

If updating

```shell
$ docker-compose up --build
```

